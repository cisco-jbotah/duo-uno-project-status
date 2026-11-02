# Duo Uno Project Status Summary

**Initiative:** Duo Uno  
**Source:** [Squad Goals - Duo Uno Initiative](https://things.cisco.com/app/squad-goals/initiatives/cmvr2rmnb0004mr36uuprjw3e?from=%2F)  
**Last Updated:** 2026-11-02

---

## 1. Platform Scalability / Resilience

### Kafka Upgrade for Event Streams & Customer Logging Platform
**Status:** Active  
**Squad:** Kafka Upgrade

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTDP-62 | Upgrade all Event Streams MSK clusters to Kafka 3.8.x | Planned |
| ZTDP-38 | Upgrade all CLP MSK clusters to Kafka 3.9.x | Active |
| ZTDP-28 | Migrate kafka-event DDI broker to Apache Kafka 3.9.2 | Done |
| ZTDP-23 | Migrate clp-kafka DDI image to Apache Kafka 3.9.X | Done |
| ZTDP-105 | Event Streams MSK 3.8 Upgrade Dev Pilot | Active |

### Migrate Omni to K8s
**Status:** Active  
**Squad:** Omni on K8s

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTOP-2749 | Migrate haomni-first to K8s | Done |
| ZTOP-2754 | Migrate haomni-zt-prod to K8s | Active |

### Uno Performance Testing Stabilization
**Status:** Active  
**Squad:** Performance Testing Platform Stabilization

**FY27 Q2 Outcomes:**
- Stabilization of performance testing platform (epics tracked in Squad Goals)

### FIPS 140-3 Compliance
**Status:** Active  
**Squad:** FIPS 140-3 Compliance

**FY27 Q2 Outcomes (Active/Planned — 100 total epics, highlights below):**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTFP-168 | Customer Controlled - Update Duo Windows Internal to FIPS 140-3 | Active |
| ZTFP-170 | Customer Controlled - Update Legacy AD Authentication to FIPS 140-3 | Active |
| ZTFP-173 | Customer Controlled - Update Duo Remote Desktop Services: Gateway to FIPS 140-3 | Active |
| ZTFP-177 | Customer Controlled - Update FS: AD FS on Windows Server 2016+ to FIPS 140-3 | Active |
| ZTFP-181 | Customer Controlled - Update Duo Windows Logon to FIPS 140-3 | Active |
| ZTFP-193 | Update Greenhouse to FIPS 140-3 | Active |
| ZTFP-172 | Customer Controlled - Update DuoConnect: Windows, MacOS, Linux to FIPS 140-3 | Planned |
| ZTFP-175 | Customer Controlled - Update Duo Remote Desktop Services: Web Access to FIPS 140-3 | Planned |
| ZTFP-176 | Customer Controlled - Update Duo OWA - Outlook Web Access to FIPS 140-3 | Planned |
| ZTFP-178 | Customer Controlled - Update Duo Epic for Hyperdrive to FIPS 140-3 | Planned |
| ZTFP-182 | SRE deploys product/services using FIPS 140-3 to FedRAMP High (govcloud) | Planned |
| ZTFP-183 | SRE deploys products/services using FIPS 140-3 to FedRAMP Moderate (govcloud) | Planned |
| ZTFP-185 | SRE deploys commercial features with FIPS 140-3 to FedRAMP Moderate + High (govcloud) | Planned |
| ZTFP-186 | Customer Controlled - Update DNG: DNS Container to FIPS 140-3 | Planned |
| ZTFP-187 | Customer Controlled - Update DNG: Redis Container to FIPS 140-3 | Planned |
| ZTFP-188 | Customer Controlled - Update DNG Portal Container to FIPS 140-3 | Planned |
| ZTFP-189 | Customer Controlled - Update DNG: Admin Container to FIPS 140-3 | Planned |
| ZTFP-190 | Update SSO - Cloud SSO to FIPS 140-3 | Planned |
| ZTFP-192 | Update SSO - Keychain to FIPS 140-3 | Planned |

### PQC Compliance: TLS 1.3
**Status:** Active  
**Squad:** PQC Research & Planning

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTFP-330 | PQC Research: On-Prem Platform - iOS | Active |
| ZTFP-332 | PQC Research: On-Prem Platform - Android | Active |
| ZTFP-336 | PQC Research: On-Prem Platform - Windows / Duo Desktop | Planned |
| ZTFP-338 | PQC Research: On-Prem Platform - Windows / Secure Remote Access | Planned |
| ZTFP-341 | PQC Research: On-Prem Platform - Linux / Duo Desktop | Planned |
| ZTFP-342 | PQC Research: On-Prem Platform - Linux / Secure Remote Access | Planned |
| ZTFP-343 | PQC Research: SRE | Planned |
| ZTFP-380 | PQC Research: Duo SSO | Planned |

### Phase 3: Duo FedRAMP High Feature Parity Completion (GC SCN7)
**Status:** Active  
**Squads:** Greenhouse in FedRAMP, Seedling in FedRAMP, FedRAMP SSO, RBA in FedRAMP

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTDC-1320 | Update Greenhouse to FIPS 140-3 | Active |
| ZTDC-1088 | Seedling in FedRAMP High (Dev) | Active |
| ZTDC-1288 | Greenhouse in FedRAMP High | Planned |
| ZTDC-1266 | Seedling in FedRAMP High (Stage) | Planned |
| ZTFRH-2309 | F9 Staging - Audit readiness | Planned |
| ZTFRH-2043 | F9 Staging - CloudSSO Deployment | Done |
| ZTFRH-3 | Risk-based Authentication | Done |

---

## 2. Features

### A. Migration

#### Firehose Kubernetes Migration Support
**Target:** Firehose on Kubernetes by July 2027

**FY27 Q2 Outcomes:**
- Kubernetes migration for Firehose services (tracked in Squad Goals initiative)

#### Web Framework Migration
**FY27 Q2 Outcomes:**
- Web framework modernization efforts (tracked in Squad Goals initiative)

#### KSA Migration
**FY27 Q2 Outcomes:**
- KSA region migration work (tracked in Squad Goals initiative)

#### SSO Redis to Valkey Migration
**Status:** Planned  
**Squad:** Duo SSO Systems

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTSSO-10294 | SSO: Redis to Valkey Migration | Planned |

#### SSO Flip N Crypt
**Status:** Active  
**Squad:** Duo SSO Systems

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTSSO-10187 | SSO Flip-N-Crypt | Active |

#### Migrate Omni to K8s
**Status:** Active  
**Squad:** Omni on K8s

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTOP-2749 | Migrate haomni-first to K8s | Done |
| ZTOP-2754 | Migrate haomni-zt-prod to K8s | Active |

#### Migration of Domestic VOIP Traffic to Webex Connect
**Status:** Active  
**Squad:** Telephony - Webex Connect

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTPS-1979 | More traffic with Webex Connect, check Visibility and Readiness | Done |

---

### B. Mythos Remediation

#### Duo Uno - Mythos Findings Remediation
**Status:** Active  
**Squads:** WinLogon, Duo SSO - Mythos Remediation

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTOSL-3088 | Winlogon Mythos Epic | Active |
| ZTOSL-2964 | [WinLogon] WinLogon Testing Improvements | Active |
| ZTSSO-10296 | SSO Flashpoint Epic | Active |

---

### C. CRA Compliance

#### CRA Compliance
**Status:** Active  
**Squads:** CRA Compliance Squad, CRA Compliance, Endpoint Access Trust Compliance, Applications, Applications - CRA Compliance

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTOSL-2831 | Winlogon - CRA Manual Control Review | Active |
| ZTOSL-2853 | MacLogon - CRA Manual Control Review | Active |
| ZTEA-1291 | Legacy AD Authentications - CRA Manual Control Review | Active |
| ZTEA-1542 | ADFS 2.4.2 - Salesforce Claim Support | Active |
| ZTFP-415 | CRA Manual Control Review | Planned |
| ZTAT-1721 | CRA Compliance - Gap Analysis | Planned |
| ZTEA-1252 | ADFS - CRA Manual Control Review | Done |
| ZTEA-1271 | RDGateway - CRA Manual Control Review | Done |
| ZTEA-1290 | Hyperdrive - CRA Manual Control Review | Done |
| ZTEA-1292 | OWA/RDWeb - CRA Manual Control Review | Done |
| ZTEA-1293 | Windows SSH - CRA Manual Control Review | Done |

---

### D. Auth & Identity Features

#### Auth & IDP Feature Delivery
**Status:** Active  
**Squads:** Dark Mode, Unsupported Browser Report, Self Service Password Reset, Unification Rollout, PWL in Fed, Frameless v3 Deprecation

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTAUTH-2282 | Dark Mode Enablement for Lee in Prompt | Active |
| ZTAUTH-1702 | Unsupported Browser Report | Active |
| ZTUNIFIED-1760 | promptserv engine-factor refactor: one owner per authentication | Active |
| ZTUNIFIED-1373 | FE Test Improvements | Active |
| ZTMTTR-1475 | Unblock cloudsso migrations for customers that use PWL | Done |
| ZTFRH-2999 | Passwordless F9 Moderate Production | Planned |
| ZTFRH-2998 | Passwordless F9 High Production | Planned |

#### SSO Single Log Out
**Status:** Active  
**Squad:** SSO Single Log Out

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTSSO-10326 | SAML Single Logout (SLO) | Planned |

#### AAL3 Admin Authentication
**Status:** Active  
**Squad:** AAL3 Admin Authentication

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTAEX-2740 | Admin Panel AAL3 Smart Card and Owner Break-Glass Controls | Active |

#### Global/Shared Authorization Server
**Status:** Active  
**Squad:** Global/Shared Authz Server

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTSSO-9286 | Shared Authorization Server | Planned |

---

### E. Endpoint & Device Features

#### Mobile GPS Location-Aware Access Policy
**Status:** Active  
**Squad:** Duo Device - Mobile GPS

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTMOBILE-4669 | GPS Milestone 3: enforce geo location | Active |
| ZTMOBILE-4630 | GPS Milestone 4: Handle all unhappy paths | Active |
| ZTMOBILE-4799 | GPS Milestone 5: Complete UI | Active |
| ZTMOBILE-4619 | GPS Milestone 2: Policy control enforces presence of GPS data | Done |
| ZTMOBILE-4497 | GPS Milestone 1: Initial research and skeleton round-trip | Done |

#### Mobile AiTM-Resistant Authentication
**Status:** Active  
**Squad:** Duo Device - Mobile AiTM

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTMOBILE-4509 | Milestone 9: post GA high value low lift improvements (AITM) | Active |
| ZTMOBILE-5026 | Milestone 8: MVP to GA, phase ii | Active |
| ZTMOBILE-4913 | Milestone 7: MVP to GA, post attack detection pivot, phase i | Done |
| ZTMOBILE-4594 | Milestone 6: MVP to GA, core | Done |

#### Duo Desktop Secure Platform & Compliance
**Status:** Active  
**Squad:** Duo Device - Desktop

**FY27 Q2 Outcomes:**
- Desktop secure platform and compliance epics (tracked in Squad Goals)

#### Trusted Endpoint Ecosystem Expansion
**Status:** Active  
**Squads:** Trusted Endpoints, Duo Device - Trusted Endpoint

**FY27 Q2 Outcomes:**
- Trusted endpoint ecosystem expansion epics (tracked in Squad Goals)

#### Endpoint Administration Platform
**Status:** Active  
**Squad:** Duo Device - Endpoint Administration

**FY27 Q2 Outcomes:**
- Endpoint administration platform epics (tracked in Squad Goals)

#### Agentic Detection & Endpoint Intelligence
**Status:** Active  
**Squad:** Agentic Detection

**FY27 Q2 Outcomes:**
- Agentic detection and endpoint intelligence epics (tracked in Squad Goals)

#### CA Pinning Improvements
**Status:** Active

**FY27 Q2 Outcomes:**
- CA pinning improvements (tracked in Squad Goals)

#### IDV with CLEAR
**Status:** Active

**FY27 Q2 Outcomes:**
- Identity verification with CLEAR integration (tracked in Squad Goals)

---

### F. Access & Identity Management

#### Duo Passport - Sessions Bridge
**Status:** Active  
**Squad:** Duo Passport

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTDS-1803 | DVC Client EXE Conversion | Active |
| ZTDS-1804 | DVC Channel Authentication | Active |
| ZTDS-1805 | RDP Virtual Channel Lifecycle Management | Active |
| ZTDS-1806 | Session Bridge Authlogs | Done |
| ZTDS-1622 | Session Bridge Improvements | Done |
| ZTDS-1621 | Session Bridge Beta | Done |

#### Duo Authentication Decision Service
**Status:** Active  
**Squad:** AD Defense

**FY27 Q2 Outcomes:**
- Authentication decision service development (tracked in Squad Goals)

#### Directory Sync & Provisioning Modernization
**Status:** Active  
**Squad:** Directory Sync & Provisioning

**FY27 Q2 Outcomes:**
- Directory sync modernization epics (tracked in Squad Goals)

#### Admin Experience & Custom Roles
**Status:** Active  
**Squad:** Duo Admin Experience

**FY27 Q2 Outcomes:**
- Admin experience and custom roles epics (tracked in Squad Goals)

#### Desktop Login Passwordless & Modernization
**Status:** Active  
**Squad:** MacLogon

**FY27 Q2 Outcomes:**
- MacLogon passwordless and modernization epics (tracked in Squad Goals)

#### Windows Logon Credential Modernization
**Status:** Active

**FY27 Q2 Outcomes:**
- Windows logon credential modernization (tracked in Squad Goals)

#### WinLogon - Inline Enrollment
**Status:** Active

**FY27 Q2 Outcomes:**
- WinLogon inline enrollment (tracked in Squad Goals)

---

### G. Business & Partner Features

#### Admin API Enhancements For Vodafone
**Status:** Active  
**Squad:** Admin API Enhancements

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTMSPG-413 | Admin API Enhancements - Vodafone API | Active |

#### MSP Sub-account Trials
**Status:** Active  
**Squad:** MSP Sub-account Trials

**FY27 Q2 Outcomes:**
- MSP sub-account trials epics (tracked in Squad Goals)

#### MSP PSA Automation
**Status:** Active  
**Squad:** MSP PSA Automation

**FY27 Q2 Outcomes:**
- MSP PSA automation epics (tracked in Squad Goals)

#### Zero Trust Suites SKU
**Status:** Active  
**Squad:** Zero Trust Suites SKU

**FY27 Q2 Outcomes:**
- Zero Trust Suites SKU development (tracked in Squad Goals)

---

### H. PAM & Secure Access

#### PAM Teleport Integration
**Status:** Active  
**Squad:** PAM Teleport Integration

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTTANGO-13 | Architecture Decisions | Done |
| ZTTANGO-22 | Pipeline Orchestration Layer / Create Workload Cluster | Done |
| ZTTANGO-78 | Deploy to first | Done |
| ZTTANGO-79 | Private preview: deploy to production | Done |
| ZTTANGO-149 | Onboarding pipeline hardening | Done |
| ZTTANGO-100 | Enable Teleport Integration from Cisco Cloud Control | Done |
| ZTTANGO-88 | Observability | Done |

*All 16 epics completed.*

---

## 3. Team Stabilization

### Building Uno Capability Matrix
**Status:** Active  
**Squads:** Duo Uno Eng Leads, Automating Maintenance Work on Business Systems, Duo Release & Docs

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTDP-107 | Duo Uno Focused Areas and Responsibilities | Active |

### Duo Uno Cross Training Plan
**Status:** Active  
**Squad:** Duo Uno Cross Training

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTDP-53 | Duo Uno Cross Training | Active |

### Duo Uno On Call Rotation Process
**Status:** Active  
**Squad:** Duo Uno On Call Rotation

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTDP-51 | Duo Uno On-Call Rotation Process Change | Planned |

### Duo Uno - Project SDLC Changes
**Status:** Active  
**Squad:** Duo Uno - Project SDLC Changes

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTDP-185 | Duo Uno - Project SDLC Changes | Planned |

### Duo Uno - Project Architecture Changes & Deprecations
**Status:** Active  
**Squad:** Duo Uno - Project Architecture Changes & Deprecations

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTDP-122 | Duo Uno - Project Architecture Changes & Deprecations | Planned |

### Duo Uno Observability and Visibility
**Status:** Active  
**Squad:** Duo Uno Observability

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTDP-52 | Duo Uno Visibility and Observability | Active |

### Duo Uno Tools, & Systems
**Status:** Active  
**Squads:** Duo Uno Tools and Systems, Scaffold - Beta Portal, Scaffold - PM Research Tool

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTDP-189 | Setup Duo Uno Architecture Program | Done |
| ZTDP-49 | Duo Uno Tools and Systems | Active |
| ZTDP-335 | Streamlining vulnerability handling | Planned |

### Duo Code Ownership Aligns to the New Organization
**Status:** Active  
**Squad:** Duo Code Ownership

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTDP-86 | Audit and Realign cisco-sbg Code Ownership | Active |

---

## 4. Support Reduction

### Duo Uno Support Escalation Process Change
**Status:** Active  
**Squad:** Escalation

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| ZTDP-50 | Duo Uno Support Escalation Process Change | Active |

### Escalation Intelligence & Orchestration
**Status:** Active  
**Squad:** Escalation Intelligence & Orchestration

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| RUNWAY-172 | Webex /escalate creates a request record | Active |
| RUNWAY-173 | Jira ticket created from a request record | Active |
| RUNWAY-177 | Team router invoked and appended to ticket | Active |
| RUNWAY-178 | Expand ZT-Recall connectors | Active |
| RUNWAY-179 | Knowledge invoked and appended to ticket | Active |
| RUNWAY-174 | Salesforce visibility added to Jira | Done |
| RUNWAY-176 | Route Jira tickets to the appropriate team | Done |
| RUNWAY-175 | Notification ladder configured for Jira ticket management | Planned |

### Escalation Intelligence
**Status:** Active  
**Squad:** Escalation Intelligence

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| RUNWAY-51 | Epic 8 - Enriched with logs and a probable cause | Done |

### Code Review Modernization
**Status:** Active  
**Squad:** Code review modernization

**FY27 Q2 Outcomes:**
| Jira ID | Epic | Status |
|---------|------|--------|
| RUNWAY-3 | Explore larger removal of CODEOWNERS from all "non-critical" surface area and implement | Active |
| RUNWAY-11 | Metrics gathering, dashboards, and review health tooling | Active |
| RUNWAY-12 | Improve tooling to keep teams aware of outstanding PRs for review | Active |
| RUNWAY-6 | Productionize risk-based code review | Planned |
| RUNWAY-10 | Understand the shape of PRs | Planned |
| RUNWAY-2 | Identify review surface area with "too many" owners and remove from CODEOWNERS | Done |
| RUNWAY-4 | Build PoC of AI and rules-based replacement for CODEOWNERS | Done |
| RUNWAY-5 | Reduce time to PR approval by replacing CODEOWNERS with this system | Done |

---

## Summary by Category

| Category | Outcomes | Active Epics | Done | Planned |
|----------|----------|-------------|------|---------|
| **Platform Scalability / Resilience** | 6 | Multiple | Multiple | Multiple |
| **Features** | 26+ | Multiple | Multiple | Multiple |
| **Team Stabilization** | 8 | Multiple | Multiple | Multiple |
| **Support Reduction** | 4 | Multiple | Multiple | Multiple |

---

*Data sourced from Squad Goals initiative and local JSON exports. Items marked "tracked in Squad Goals" need direct verification from the [initiative page](https://things.cisco.com/app/squad-goals/initiatives/cmvr2rmnb0004mr36uuprjw3e?from=%2F).*
