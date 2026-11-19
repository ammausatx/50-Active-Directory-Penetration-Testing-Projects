# Project 47 — Hybrid Active Directory and Entra ID Security Assessment

**Advanced | Enterprise Active Directory assessment | Authorized lab framework**

## Objective
Assess identity synchronization, privileged role separation, conditional access, hybrid authentication, and legacy protocol exposure across on-premises AD and Microsoft Entra ID.

## Scope and safety
Use only the isolated `adlab.test` lab and synthetic identities unless a separate written engagement authorizes additional assets. Define written scope, exclusions, stop conditions, emergency contacts, and evidence handling. Do not perform unauthorized access, credential theft, persistence, ticket forgery, or destructive actions.

## Prerequisites
Projects 01–45 as applicable; current lab snapshot; approved tool versions; documented authorization and rules of engagement; secure evidence storage.

## 1. Preparation
Confirm objectives, targets, system owners, allowed methods, testing window, monitoring contacts, and rollback/stop procedures. Record the baseline.

![Configuration](screenshots/47-01-configuration.svg)

## 2. Walkthrough
### Step 1 — Inventory Entra Connect/Cloud Sync topology, sync scope, staging servers, and service identity design.

Use the approved read-only administrative view or query. Record exact tool version, timestamp, account context, and sanitized output. Validate the observation with the relevant owner; do not make changes during discovery.

### Step 2 — Compare on-prem AD admins, Entra roles, sync operators, and emergency access accounts.

Use the approved read-only administrative view or query. Record exact tool version, timestamp, account context, and sanitized output. Validate the observation with the relevant owner; do not make changes during discovery.

### Step 3 — Review Conditional Access/MFA coverage for administrators, legacy authentication, and device compliance.

Use the approved read-only administrative view or query. Record exact tool version, timestamp, account context, and sanitized output. Validate the observation with the relevant owner; do not make changes during discovery.

### Step 4 — Assess hybrid authentication design, monitoring, break-glass accounts, and recovery procedures.

Use the approved read-only administrative view or query. Record exact tool version, timestamp, account context, and sanitized output. Validate the observation with the relevant owner; do not make changes during discovery.

![Execution](screenshots/47-02-execution.svg)

## 3. Example observations (synthetic)
- **OBS-47-1:** Sync server or service identity has excessive privilege.
- **OBS-47-2:** On-prem and cloud privileged roles overlap without separation.
- **OBS-47-3:** Conditional Access exclusions are broad or permanent.

These are training scenarios, not assertions about a real environment. Validate evidence and business context before assigning severity.

## 4. Evidence and risk
For each confirmed finding, record unique ID, title, severity, confidence, affected assets, sanitized object identifiers, evidence source and timestamp, account context, preconditions, technical/business impact, control mapping, owner, and due date. Never include passwords, hashes, ticket blobs, private keys, tokens, or unnecessary personal data.

## 5. Remediation
- Harden sync infrastructure and restrict administrative access.
- Separate cloud and on-prem privileged identities.
- Require strong MFA and disable legacy authentication after compatibility review.

![Findings](screenshots/47-03-findings.svg)

## 6. Detection and retest
Correlate relevant DC, endpoint, CA, identity-provider, and network telemetry. Audit availability depends on configuration. Validate approved remediation using repeatable read-only checks and document residual risk.

## 7. Completion checklist
- [ ] Authorization, scope, exclusions, and stop conditions recorded.
- [ ] Baseline and methodology documented.
- [ ] Assessment performed within approved boundaries.
- [ ] Findings validated and evidence sanitized.
- [ ] Critical findings communicated through agreed channels.
- [ ] Remediation owners and retest criteria assigned.
- [ ] Final report peer-reviewed and securely delivered.

## References
- https://learn.microsoft.com/en-us/entra/identity/hybrid/
- https://learn.microsoft.com/en-us/entra/identity/conditional-access/overview
- https://learn.microsoft.com/en-us/entra/identity/role-based-access-control/best-practices

## Disclaimer
For authorized assessment and training use only. Screenshots and sample observations are simulated training illustrations, not genuine tool captures or customer assessment evidence.
