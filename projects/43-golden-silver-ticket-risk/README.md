# Project 43 — Golden Ticket and Silver Ticket Security Assessment

**Advanced | Enterprise Active Directory security assessment | Read-only validation**

## Objective
Assess controls protecting the Kerberos krbtgt and service account keys, ticket lifetime policy, privileged identity hygiene, and detection. No forged tickets are created or used.

## Scope and safety
Use only the isolated `adlab.test` lab and synthetic identities. Obtain written authorization and define exclusions and stop conditions. Do not perform credential replay, lateral movement, persistence, ticket forgery, or unauthorized access.

## Prerequisites
Projects 01–40 as applicable; current lab snapshot; approved administrative tools; documented scope, owners, and evidence handling.

## 1. Prepare
Confirm target systems, account context, source host, authorization, and assessment window. Record baseline configuration.

![Configuration](screenshots/43-01-configuration.svg)

## 2. Walkthrough
### Step 1 — Review krbtgt metadata using Get-ADUser krbtgt -Properties Enabled,PasswordLastSet,msDS-SupportedEncryptionTypes.

Use the approved read-only administrative view or query. Record tool version, timestamp, account context, and sanitized output. Validate the observation with the relevant system owner; do not modify settings during discovery.

### Step 2 — Review documented krbtgt rotation and forest recovery procedures with the AD owner.

Use the approved read-only administrative view or query. Record tool version, timestamp, account context, and sanitized output. Validate the observation with the relevant system owner; do not modify settings during discovery.

### Step 3 — Inventory privileged SPN-bearing accounts and evaluate gMSA/password management.

Use the approved read-only administrative view or query. Record tool version, timestamp, account context, and sanitized output. Validate the observation with the relevant system owner; do not modify settings during discovery.

### Step 4 — Review Kerberos telemetry for abnormal ticket lifetimes, encryption types, and service access.

Use the approved read-only administrative view or query. Record tool version, timestamp, account context, and sanitized output. Validate the observation with the relevant system owner; do not modify settings during discovery.

![Execution](screenshots/43-02-execution.svg)

## 3. Example observations (synthetic)
- **OBS-43-1:** krbtgt rotation procedure is undocumented or untested.
- **OBS-43-2:** Privileged service accounts use unmanaged long-lived passwords.
- **OBS-43-3:** Kerberos ticket anomaly monitoring is absent.

These are training examples, not claims about your environment. Confirm the complete configuration and business context before assigning severity.

## 4. Evidence and risk
Record sanitized asset/object identifiers, source and timestamp, relevant policy/attribute, account context, expected versus observed state, attack preconditions, impact, confidence, and owner. Do not publish passwords, hashes, tickets, private keys, or personal data.

## 5. Remediation
- Maintain and test a documented krbtgt rotation and recovery plan.
- Migrate service identities to gMSA where feasible.
- Modernize Kerberos encryption and monitor abnormal ticket patterns.

![Findings](screenshots/43-03-findings.svg)

## 6. Detection and retest
Review applicable DC, endpoint, authentication, and identity telemetry. Audit availability depends on policy and logging configuration. After approved remediation, repeat read-only checks and document residual risk.

## 7. Completion checklist
- [ ] Scope and authorization confirmed.
- [ ] Baseline and tool versions recorded.
- [ ] Assessment completed without unauthorized access or changes.
- [ ] Findings validated and evidence sanitized.
- [ ] Remediation owners and due dates assigned.
- [ ] Retest and residual risk documented.

## References
- https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/manage/forest-recovery-guide/ad-forest-recovery-guide
- https://attack.mitre.org/techniques/T1558/001/
- https://attack.mitre.org/techniques/T1558/002/

## Disclaimer
For authorized lab use only. Screenshots and sample observations are simulated training illustrations, not genuine tool captures or customer assessment evidence.
