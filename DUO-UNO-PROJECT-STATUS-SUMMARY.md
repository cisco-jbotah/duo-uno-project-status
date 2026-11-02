# Duo Uno Project Status Summary

**Initiative:** Duo Uno  
**Source:** [Squad Goals](https://things.cisco.com/app/squad-goals/initiatives/cmvr2rmnb0004mr36uuprjw3e?from=%2F)  
**Last Updated:** 2026-11-02  
**Total Outcomes:** 41

---

## 1. Platform Scalability / Resilience

### 1.1 Kafka Upgrade for Event Streams & Customer Logging Platform
**Outcome Status:** Active | **Squad:** Kafka Upgrade

| Jira | Epic | Status |
|------|------|--------|
| ZTDP-38 | Upgrade all CLP MSK clusters to Kafka 3.9.x | Active |
| ZTDP-105 | Event Streams MSK 3.8 Upgrade Dev Pilot | Active |
| ZTDP-62 | Upgrade all Event Streams MSK clusters to Kafka 3.8.x | Planned |
| ZTDP-28 | Migrate kafka-event DDI broker to Apache Kafka 3.9.2 | Done |
| ZTDP-23 | Migrate clp-kafka DDI image to Apache Kafka 3.9.X | Done |

### 1.2 Migrate Omni to K8s
**Outcome Status:** Active | **Squad:** Omni on K8s

| Jira | Epic | Status |
|------|------|--------|
| ZTOP-2754 | Migrate haomni-zt-prod to K8s | Active |
| ZTOP-2749 | Migrate haomni-first to K8s | Done |

### 1.3 Uno Performance Testing Stabilization
**Outcome Status:** Active | **Squad:** Performance Testing Platform Stabilization

> Epics tracked in Squad Goals — no Jira epics in current export.

### 1.4 FIPS 140-3 Compliance
**Outcome Status:** Active | **Squad:** FIPS 140-3 Compliance  
**Progress:** 81 Done / 6 Active / 13 Planned (100 total epics)

**Active:**
| Jira | Epic | Status |
|------|------|--------|
| ZTFP-168 | Update Duo Windows Internal to FIPS 140-3 | Active |
| ZTFP-170 | Update Legacy AD Authentication to FIPS 140-3 | Active |
| ZTFP-173 | Update Duo Remote Desktop Services: Gateway to FIPS 140-3 | Active |
| ZTFP-177 | Update AD FS on Windows Server 2016+ to FIPS 140-3 | Active |
| ZTFP-181 | Update Duo Windows Logon to FIPS 140-3 | Active |
| ZTFP-193 | Update Greenhouse to FIPS 140-3 | Active |

**Planned:**
| Jira | Epic | Status |
|------|------|--------|
| ZTFP-172 | Update DuoConnect: Windows, MacOS, Linux to FIPS 140-3 | Planned |
| ZTFP-175 | Update Duo Remote Desktop Services: Web Access to FIPS 140-3 | Planned |
| ZTFP-176 | Update Duo OWA - Outlook Web Access to FIPS 140-3 | Planned |
| ZTFP-178 | Update Duo Epic for Hyperdrive to FIPS 140-3 | Planned |
| ZTFP-182 | SRE deploys to FedRAMP High (govcloud) | Planned |
| ZTFP-183 | SRE deploys to FedRAMP Moderate (govcloud) | Planned |
| ZTFP-185 | SRE deploys commercial features to FedRAMP Mod+High | Planned |
| ZTFP-186 | Update DNG: DNS Container to FIPS 140-3 | Planned |
| ZTFP-187 | Update DNG: Redis Container to FIPS 140-3 | Planned |
| ZTFP-188 | Update DNG Portal Container to FIPS 140-3 | Planned |
| ZTFP-189 | Update DNG: Admin Container to FIPS 140-3 | Planned |
| ZTFP-190 | Update SSO - Cloud SSO to FIPS 140-3 | Planned |
| ZTFP-192 | Update SSO - Keychain to FIPS 140-3 | Planned |

### 1.5 PQC Compliance: TLS 1.3
**Outcome Status:** Active | **Squad:** PQC Research & Planning  
**Progress:** 9 Done / 2 Active / 6 Planned

| Jira | Epic | Status |
|------|------|--------|
| ZTFP-330 | PQC Research: On-Prem Platform — iOS | Active |
| ZTFP-332 | PQC Research: On-Prem Platform — Android | Active |
| ZTFP-336 | PQC Research: Windows / Duo Desktop | Planned |
| ZTFP-338 | PQC Research: Windows / Secure Remote Access | Planned |
| ZTFP-341 | PQC Research: Linux / Duo Desktop | Planned |
| ZTFP-342 | PQC Research: Linux / Secure Remote Access | Planned |
| ZTFP-343 | PQC Research: SRE | Planned |
| ZTFP-380 | PQC Research: Duo SSO | Planned |

### 1.6 Phase 3: Duo FedRAMP High Feature Parity Completion (GC SCN7)
**Outcome Status:** Active | **Squads:** Greenhouse in FedRAMP, Seedling in FedRAMP, FedRAMP SSO, RBA in FedRAMP

| Jira | Epic | Squad | Status |
|------|------|-------|--------|
| ZTDC-1320 | Update Greenhouse to FIPS 140-3 | Greenhouse in FedRAMP | Active |
| ZTDC-1088 | Seedling in FedRAMP High (Dev) | Seedling in FedRAMP | Active |
| ZTDC-1288 | Greenhouse in FedRAMP High | Greenhouse in FedRAMP | Planned |
| ZTDC-1266 | Seedling in FedRAMP High (Stage) | Seedling in FedRAMP | Planned |
| ZTFRH-2309 | F9 Staging - Audit readiness | FedRAMP SSO | Planned |
| ZTFRH-2043 | F9 Staging - CloudSSO Deployment | FedRAMP SSO | Done |
| ZTFRH-3 | Risk-based Authentication | RBA in FedRAMP | Done |

---

## 2. Features

### A. Migration

#### Firehose Kubernetes Migration Support
**Target:** Firehose on Kubernetes by July 2027

> Tracked in Squad Goals initiative.

#### Web Framework Migration

> Tracked in Squad Goals initiative.

#### KSA Migration

> Tracked in Squad Goals initiative.

#### SSO Redis to Valkey Migration
**Outcome:** Duo SSO | **Squad:** Duo SSO Systems

| Jira | Epic | Status |
|------|------|--------|
| ZTSSO-10294 | SSO: Redis to Valkey Migration | Planned |

#### SSO Flip N Crypt
**Outcome:** Duo SSO | **Squad:** Duo SSO Systems

| Jira | Epic | Status |
|------|------|--------|
| ZTSSO-10187 | SSO Flip-N-Crypt | Active |

#### Migrate Omni to K8s
**Squad:** Omni on K8s

| Jira | Epic | Status |
|------|------|--------|
| ZTOP-2754 | Migrate haomni-zt-prod to K8s | Active |
| ZTOP-2749 | Migrate haomni-first to K8s | Done |

#### Migration of Domestic VOIP Traffic to Webex Connect
**Outcome Status:** Active | **Squad:** Telephony - Webex Connect

| Jira | Epic | Status |
|------|------|--------|
| ZTPS-1979 | More traffic with Webex Connect, check Visibility and Readiness | Done |

---

### B. Mythos Remediation

#### Duo Uno - Mythos Findings Remediation
**Outcome Status:** Active | **Squads:** WinLogon, Duo SSO - Mythos Remediation

| Jira | Epic | Squad | Status |
|------|------|-------|--------|
| ZTOSL-3088 | Winlogon Mythos Epic | WinLogon | Active |
| ZTOSL-2964 | WinLogon Testing Improvements | WinLogon | Active |
| ZTSSO-10296 | SSO Flashpoint Epic | Duo SSO - Mythos Remediation | Active |

---

### C. CRA Compliance

#### CRA Compliance
**Outcome Status:** Active  
**Squads:** CRA Compliance Squad, CRA Compliance, Endpoint Access Trust Compliance, Applications, Applications - CRA Compliance

| Jira | Epic | Squad | Status |
|------|------|-------|--------|
| ZTOSL-2831 | Winlogon — CRA Manual Control Review | CRA Compliance Squad | Active |
| ZTOSL-2853 | MacLogon — CRA Manual Control Review | CRA Compliance Squad | Active |
| ZTEA-1291 | Legacy AD Authentications — CRA Manual Control Review | CRA Compliance Squad | Active |
| ZTEA-1542 | ADFS 2.4.2 - Salesforce Claim Support | Endpoint Access Trust | Active |
| ZTFP-415 | CRA Manual Control Review | CRA Compliance | Planned |
| ZTAT-1721 | CRA Compliance - Gap Analysis | Applications - CRA | Planned |
| ZTEA-1252 | ADFS — CRA Manual Control Review | CRA Compliance Squad | Done |
| ZTEA-1271 | RDGateway — CRA Manual Control Review | CRA Compliance Squad | Done |
| ZTEA-1290 | Hyperdrive — CRA Manual Control Review | CRA Compliance Squad | Done |
| ZTEA-1292 | OWA/RDWeb — CRA Manual Control Review | CRA Compliance Squad | Done |
| ZTEA-1293 | Windows SSH — CRA Manual Control Review | CRA Compliance Squad | Done |

---

### D. Auth & Identity

#### Auth & IDP Feature Delivery
**Outcome Status:** Active  
**Squads:** Dark Mode, Unsupported Browser Report, Self Service Password Reset, Unification Rollout, PWL in Fed, Frameless v3 Deprecation

| Jira | Epic | Squad | Status |
|------|------|-------|--------|
| ZTAUTH-2282 | Dark Mode Enablement for Lee in Prompt | Dark Mode | Active |
| ZTAUTH-1702 | Unsupported Browser Report | Unsupported Browser Report | Active |
| ZTUNIFIED-1760 | promptserv engine-factor refactor: one owner per auth | Unification Rollout | Active |
| ZTUNIFIED-1373 | FE Test Improvements | Unification Rollout | Active |
| ZTMTTR-1475 | Unblock cloudsso migrations for PWL customers | Unification Rollout | Done |
| ZTFRH-2999 | Passwordless F9 Moderate Production | PWL in Fed | Planned |
| ZTFRH-2998 | Passwordless F9 High Production | PWL in Fed | Planned |

#### SSO Single Log Out
**Outcome Status:** Active | **Squad:** SSO Single Log Out

| Jira | Epic | Status |
|------|------|--------|
| ZTSSO-10326 | SAML Single Logout (SLO) | Planned |

#### AAL3 Admin Authentication
**Outcome Status:** Active | **Squad:** AAL3 Admin Authentication

| Jira | Epic | Status |
|------|------|--------|
| ZTAEX-2740 | Admin Panel AAL3 Smart Card and Owner Break-Glass Controls | Active |

#### Desktop Login Passwordless & Modernization
**Outcome Status:** Active | **Squad:** MacLogon

> Epics tracked in Squad Goals — no Jira epics in current export.

#### Windows Logon Credential Modernization
**Outcome Status:** Active

> Epics tracked in Squad Goals — no squad assigned in current export.

#### WinLogon - Inline Enrollment
**Outcome Status:** Active

> Epics tracked in Squad Goals — no squad assigned in current export.

#### Duo Authentication Decision Service
**Outcome Status:** Active | **Squad:** AD Defense

> Epics tracked in Squad Goals — no Jira epics in current export.

#### Directory Sync & Provisioning Modernization
**Outcome Status:** Active | **Squad:** Directory Sync & Provisioning

> Epics tracked in Squad Goals — no Jira epics in current export.

---

### E. Endpoint & Device

#### Mobile GPS Location-Aware Access Policy
**Outcome Status:** Active | **Squad:** Duo Device - Mobile GPS

| Jira | Epic | Status |
|------|------|--------|
| ZTMOBILE-4669 | GPS Milestone 3: enforce geo location | Active |
| ZTMOBILE-4630 | GPS Milestone 4: Handle all unhappy paths | Active |
| ZTMOBILE-4799 | GPS Milestone 5: Complete UI | Active |
| ZTMOBILE-4619 | GPS Milestone 2: Policy control enforces presence of GPS data | Done |
| ZTMOBILE-4497 | GPS Milestone 1: Initial research and skeleton round-trip | Done |

#### Mobile AiTM-Resistant Authentication
**Outcome Status:** Active | **Squad:** Duo Device - Mobile AiTM  
**Progress:** 7 Done / 2 Active

| Jira | Epic | Status |
|------|------|--------|
| ZTMOBILE-4509 | Milestone 9: post GA high value low lift improvements | Active |
| ZTMOBILE-5026 | Milestone 8: MVP to GA, phase ii | Active |
| ZTMOBILE-4913 | Milestone 7: MVP to GA, post attack detection pivot, phase i | Done |
| ZTMOBILE-4594 | Milestone 6: MVP to GA, core | Done |
| ZTMOBILE-4313 | Milestone 5: MVP for MFA proximity inline auth, Android + iOS | Done |
| ZTMOBILE-4248 | Milestone 4: MVP for PWL proximity inline auth, Android + iOS | Done |
| ZTMOBILE-4247 | Milestone 3: MVP for PWL proximity inline auth, iOS only | Done |
| ZTMOBILE-3595 | Milestone 2: Restricted end to end happy path excluding permissions | Done |
| ZTMOBILE-3594 | Milestone 1: Data collection Dashboard and Observability | Done |

#### Duo Desktop Secure Platform & Compliance
**Outcome Status:** Active | **Squad:** Duo Device - Desktop

> Epics tracked in Squad Goals — no Jira epics in current export.

#### Trusted Endpoint Ecosystem Expansion
**Outcome Status:** Active | **Squads:** Trusted Endpoints, Duo Device - Trusted Endpoint

> Epics tracked in Squad Goals — no Jira epics in current export.

#### Endpoint Administration Platform
**Outcome Status:** Active | **Squad:** Duo Device - Endpoint Administration

> Epics tracked in Squad Goals — no Jira epics in current export.

#### Agentic Detection & Endpoint Intelligence
**Outcome Status:** Active | **Squad:** Agentic Detection

> Epics tracked in Squad Goals — no Jira epics in current export.

#### CA Pinning Improvements
**Outcome Status:** Active

> Epics tracked in Squad Goals — no squad assigned in current export.

#### IDV with CLEAR
**Outcome Status:** Active

> Epics tracked in Squad Goals — no squad assigned in current export.

---

### F. Admin & Business

#### Admin Experience & Custom Roles
**Outcome Status:** Active | **Squad:** Duo Admin Experience

> Epics tracked in Squad Goals — no Jira epics in current export.

#### Admin API Enhancements For Vodafone
**Outcome Status:** Active | **Squad:** Admin API Enhancements

| Jira | Epic | Status |
|------|------|--------|
| ZTMSPG-413 | Admin API Enhancements - Vodafone API | Active |

#### Duo Passport - Sessions Bridge
**Outcome Status:** Active | **Squad:** Duo Passport  
**Progress:** 6 Done / 3 Active

| Jira | Epic | Status |
|------|------|--------|
| ZTDS-1803 | DVC Client EXE Conversion | Active |
| ZTDS-1804 | DVC Channel Authentication | Active |
| ZTDS-1805 | RDP Virtual Channel Lifecycle Management | Active |
| ZTDS-1806 | Session Bridge Authlogs | Done |
| ZTDS-1622 | Session Bridge Improvements | Done |
| ZTDS-1621 | Session Bridge Beta | Done |
| ZTDS-1522 | WinLogon session bridge alpha | Done |
| ZTDS-1490 | Session Bridge MVP | Done |
| ZTDS-1177 | Session Bridge POC | Done |

#### MSP Sub-account Trials
**Outcome Status:** Active | **Squad:** MSP Sub-account Trials

> Epics tracked in Squad Goals — no Jira epics in current export.

#### MSP PSA Automation
**Outcome Status:** Active | **Squad:** MSP PSA Automation

> Epics tracked in Squad Goals — no Jira epics in current export.

#### Zero Trust Suites SKU
**Outcome Status:** Active | **Squad:** Zero Trust Suites SKU

> Epics tracked in Squad Goals — no Jira epics in current export.

---

## 3. Team Stabilization

### 3.1 Building Uno Capability Matrix
**Outcome Status:** Active  
**Squads:** Duo Uno Eng Leads, Automating Maintenance Work on Business Systems, Duo Release & Docs

| Jira | Epic | Status |
|------|------|--------|
| ZTDP-107 | Duo Uno Focused Areas and Responsibilities | Active |

### 3.2 Duo Uno Cross Training Plan
**Outcome Status:** Active | **Squad:** Duo Uno Cross Training

| Jira | Epic | Status |
|------|------|--------|
| ZTDP-53 | Duo Uno Cross Training | Active |

### 3.3 Duo Uno On Call Rotation Process
**Outcome Status:** Active | **Squad:** Duo Uno On Call Rotation

| Jira | Epic | Status |
|------|------|--------|
| ZTDP-51 | Duo Uno On-Call Rotation Process Change | Planned |

### 3.4 Duo Uno - Project SDLC Changes
**Outcome Status:** Active | **Squad:** Duo Uno - Project SDLC Changes

| Jira | Epic | Status |
|------|------|--------|
| ZTDP-185 | Duo Uno - Project SDLC Changes | Planned |

### 3.5 Duo Uno - Project Architecture Changes & Deprecations
**Outcome Status:** Active | **Squad:** Duo Uno - Project Architecture Changes & Deprecations

| Jira | Epic | Status |
|------|------|--------|
| ZTDP-122 | Duo Uno - Project Architecture Changes & Deprecations | Planned |

### 3.6 Duo Uno Observability and Visibility
**Outcome Status:** Active | **Squad:** Duo Uno Observability

| Jira | Epic | Status |
|------|------|--------|
| ZTDP-52 | Duo Uno Visibility and Observability | Active |

### 3.7 Duo Uno Tools, & Systems
**Outcome Status:** Active  
**Squads:** Duo Uno Tools and Systems, Scaffold - Beta Portal, Scaffold - PM Research Tool

| Jira | Epic | Status |
|------|------|--------|
| ZTDP-49 | Duo Uno Tools and Systems | Active |
| ZTDP-335 | Streamlining vulnerability handling | Planned |
| ZTDP-189 | Setup Duo Uno Architecture Program | Done |

### 3.8 Duo Code Ownership Aligns to the New Organization
**Outcome Status:** Active | **Squad:** Duo Code Ownership

| Jira | Epic | Status |
|------|------|--------|
| ZTDP-86 | Audit and Realign cisco-sbg Code Ownership | Active |

---

## 4. Support Reduction

### 4.1 Duo Uno Support Escalation Process Change
**Outcome Status:** Active | **Squad:** Escalation

| Jira | Epic | Status |
|------|------|--------|
| ZTDP-50 | Duo Uno Support Escalation Process Change | Active |

---

## Quick Reference: All 41 Outcomes by Bucket

| # | Outcome | Bucket | Active Epics | Planned | Done |
|---|---------|--------|-------------|---------|------|
| 1 | Kafka Upgrade for Event Streams & CLP | Platform | 2 | 1 | 2 |
| 2 | Migrate Omni to K8s | Platform | 1 | 0 | 1 |
| 3 | Uno Performance Testing Stabilization | Platform | — | — | — |
| 4 | FIPS 140-3 Compliance | Platform | 6 | 13 | 81 |
| 5 | PQC Compliance: TLS 1.3 | Platform | 2 | 6 | 9 |
| 6 | Phase 3: FedRAMP High Parity (GC SCN7) | Platform | 2 | 3 | 2 |
| 7 | Firehose Kubernetes Migration Support | Features > Migration | — | — | — |
| 8 | Web Framework Migration | Features > Migration | — | — | — |
| 9 | KSA Migration | Features > Migration | — | — | — |
| 10 | SSO Redis to Valkey Migration | Features > Migration | 0 | 1 | 0 |
| 11 | SSO Flip N Crypt | Features > Migration | 1 | 0 | 0 |
| 12 | Migration of VOIP to Webex Connect | Features > Migration | 0 | 0 | 1 |
| 13 | Duo Uno - Mythos Findings Remediation | Features > Mythos | 3 | 0 | 0 |
| 14 | CRA Compliance | Features > CRA | 4 | 2 | 5 |
| 15 | Auth & IDP Feature Delivery | Features > Auth | 4 | 2 | 1 |
| 16 | SSO Single Log Out | Features > Auth | 0 | 1 | 0 |
| 17 | AAL3 Admin Authentication | Features > Auth | 1 | 0 | 0 |
| 18 | Desktop Login Passwordless & Modernization | Features > Auth | — | — | — |
| 19 | Windows Logon Credential Modernization | Features > Auth | — | — | — |
| 20 | WinLogon - Inline Enrollment | Features > Auth | — | — | — |
| 21 | Duo Authentication Decision Service | Features > Auth | — | — | — |
| 22 | Directory Sync & Provisioning Modernization | Features > Auth | — | — | — |
| 23 | Mobile GPS Location-Aware Access Policy | Features > Endpoint | 3 | 0 | 2 |
| 24 | Mobile AiTM-Resistant Authentication | Features > Endpoint | 2 | 0 | 7 |
| 25 | Duo Desktop Secure Platform & Compliance | Features > Endpoint | — | — | — |
| 26 | Trusted Endpoint Ecosystem Expansion | Features > Endpoint | — | — | — |
| 27 | Endpoint Administration Platform | Features > Endpoint | — | — | — |
| 28 | Agentic Detection & Endpoint Intelligence | Features > Endpoint | — | — | — |
| 29 | CA Pinning Improvements | Features > Endpoint | — | — | — |
| 30 | IDV with CLEAR | Features > Endpoint | — | — | — |
| 31 | Admin Experience & Custom Roles | Features > Admin/Biz | — | — | — |
| 32 | Admin API Enhancements For Vodafone | Features > Admin/Biz | 1 | 0 | 0 |
| 33 | Duo Passport - Sessions Bridge | Features > Admin/Biz | 3 | 0 | 6 |
| 34 | MSP Sub-account Trials | Features > Admin/Biz | — | — | — |
| 35 | MSP PSA Automation | Features > Admin/Biz | — | — | — |
| 36 | Zero Trust Suites SKU | Features > Admin/Biz | — | — | — |
| 37 | Building Uno Capability Matrix | Team Stabilization | 1 | 0 | 0 |
| 38 | Duo Uno Cross Training Plan | Team Stabilization | 1 | 0 | 0 |
| 39 | Duo Uno On Call Rotation Process | Team Stabilization | 0 | 1 | 0 |
| 40 | Duo Uno - Project SDLC Changes | Team Stabilization | 0 | 1 | 0 |
| 41 | Duo Uno - Project Architecture Changes & Deprecations | Team Stabilization | 0 | 1 | 0 |
| 42 | Duo Uno Observability and Visibility | Team Stabilization | 1 | 0 | 0 |
| 43 | Duo Uno Tools, & Systems | Team Stabilization | 1 | 1 | 1 |
| 44 | Duo Code Ownership | Team Stabilization | 1 | 0 | 0 |
| 45 | Duo Uno Support Escalation Process Change | Support Reduction | 1 | 0 | 0 |

*`—` = epics not available in current data export; verify on [Squad Goals](https://things.cisco.com/app/squad-goals/initiatives/cmvr2rmnb0004mr36uuprjw3e?from=%2F).*
