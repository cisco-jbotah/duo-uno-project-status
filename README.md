# Weekly Progress Report Skill for Claude Code

This Claude Code skill automates updating Confluence progress report pages by pulling data from Mission Control (Squad Goals) and Jira.

## What It Does

When you run `/weekly-progress-report`, Claude will:

1. **Update Progress Bars** - Calculates progress from Mission Control outcome/squad epic completion rates
2. **Update Status Pills** - Syncs status from Mission Control (Active, Planned, Done, etc.)
3. **Update Due Dates** - Fetches target due dates from linked Jira issues
4. **Update Child Features** - Populates the "Child Features" section with epics from each squad's Jira data
5. **Sort by Due Date** - Reorders cells under each heading by target due date (soonest first, stretch goals last)
6. **Calculate Overall Progress** - Computes and updates the overall program progress at the top of the page

Make sure to provide the URL to the page you want Claude to run this skill on - if starting from the template page provided, be sure to make a copy of that page and save it to the folder you would like to have it within in Confluence. 

## Prerequisites

### 1. Mission Control (Squad Goals)

Data is sourced from [Mission Control Squad Goals](https://things.cisco.com/app/squad-goals/). The skill uses local JSON exports or references the initiative page directly.

If using local exports, place these files in your home directory:
- `mc-outcomes-with-epics.json` — outcomes with associated squads and epics
- `mc-squads-epics.json` — squad-level Jira epic mappings

### 2. Confluence CLI

Install and configure the Confluence CLI:

```bash
# Install via Homebrew
brew install confluence-cli

# Create config
mkdir -p ~/.confluence-cli
cat > ~/.confluence-cli/config.json << 'EOF'
{
  "domain": "your-domain.atlassian.net",
  "email": "your-email@company.com",
  "token": "your-api-token"
}
EOF
```

Get your API token from: https://id.atlassian.com/manage-profile/security/api-tokens

### 3. Atlassian MCP (for Jira)

Set up the Atlassian MCP for Jira access. This is used to fetch due dates and epic details from Jira issues.

## Installation

Copy the skill to your Claude skills directory:

```bash
mkdir -p ~/.claude/skills/weekly-progress-report
cp SKILL.md ~/.claude/skills/weekly-progress-report/
```

## Usage

```
/weekly-progress-report <confluence-page-url>
```

### Example

```
/weekly-progress-report https://your-domain.atlassian.net/wiki/spaces/dev/pages/12345/My-Progress-Report
```

## Creating a New Progress Report Page

1. Copy the template page: `XX-XX-XXXX Agentic AI Progress Report Template - Make a Copy`. Link: https://cisco-sbg.atlassian.net/wiki/spaces/dev/pages/1425168911/XX-XX-XXXX+Agentic+AI+Progress+Report+Template+-+Make+a+Copy 
2. Rename it with the current date or the title you want it to be - it's recommended that this be a standard format for the cadence in which you plan to create these reports. The template is meant to be duplicated each week as a new report. (e.g., `05-15-2026 Agentic AI Progress Report`)
3. Update all Jira links to point to your actual issues
4. Run `/weekly-progress-report` with your new page URL

## Data Sources

| Source | Purpose |
|--------|---------|
| **Mission Control (Squad Goals)** | Initiative structure, outcomes, squads, epic mappings, progress tracking |
| **Jira (Atlassian MCP)** | Epic details, due dates, sprint assignments |
| **Confluence CLI** | Page read/write operations |

## Page Structure Requirements

For the skill to work correctly, your page should have:

- **Workstream cells** in tables, each containing:
  - A Jira link (e.g., `https://cisco-sbg.atlassian.net/browse/ZTMCP-1205`)
  - A progress bar image in each cell - the template already has a progress bar in each cell. When you run the skill, Claude will update this image for each cell. 
  - A status macro - again, the template already has this and will be updated when running this skill
  - An expandable "Child Features" section - again, the template already has this and will be updated when running this skill

- **Section headings** (e.g., "Duo", "Secure Access", "CII") to group workstreams

- **Overall progress header** showing `XX% Overall Progress (N workstreams)`

## Troubleshooting

**"Confluence CLI not found"** - Install with `brew install confluence-cli` and configure `~/.confluence-cli/config.json`.

**"Progress bar not showing"** - The skill will automatically create and upload missing progress bar SVGs.

**"Status not updating"** - Check that the Mission Control data exports are current or that the Jira epic IDs are valid and accessible.

**"Missing epic data"** - Some squads may not have Jira epics exported yet. Verify on [Squad Goals](https://things.cisco.com/app/squad-goals/).

## License

MIT
