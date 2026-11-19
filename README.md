# 50 Active Directory Penetration Testing Projects

A structured, hands-on collection of 50 Active Directory security assessment projects, progressing from foundational domain discovery to advanced enterprise attack-path analysis.

> **Lab safety:** Perform every exercise only in a domain you own or are explicitly authorized to assess. Use isolated lab networks and disposable test accounts. Password-testing exercises must use approved test identities and conservative lockout-aware limits.

## Roadmap

### Beginner — 01–15
| # | Project |
|---:|---|
| 01 | [Active Directory Penetration Testing Lab Setup](projects/01-active-directory-lab-setup/README.md) |
| 02 | [Windows Server Domain Controller Installation](projects/02-windows-server-domain-controller/README.md) |
| 03 | [Active Directory Domain and Forest Enumeration](projects/03-domain-and-forest-enumeration/README.md) |
| 04 | [Domain User and Group Enumeration](projects/04-domain-users-and-groups-enumeration/README.md) |
| 05 | [Computer and Server Enumeration](projects/05-computer-and-server-enumeration/README.md) |
| 06 | [PowerView Active Directory Enumeration](projects/06-powerview-active-directory-enumeration/README.md) |
| 07 | [LDAP Enumeration and Information Gathering](projects/07-ldap-enumeration/README.md) |
| 08 | [SMB Enumeration and Share Assessment](projects/08-smb-enumeration/README.md) |
| 09 | [SYSVOL and NETLOGON Security Assessment](projects/09-sysvol-netlogon-security/README.md) |
| 10 | [Group Policy Object (GPO) Security Assessment](projects/10-gpo-security-assessment/README.md) |
| 11 | [Password Policy and Account Lockout Assessment](projects/11-password-policy-account-lockout/README.md) |
| 12 | [Password Spraying Risk Assessment](projects/12-password-spraying-risk-assessment/README.md) |
| 13 | [Kerberos Authentication Fundamentals](projects/13-kerberos-authentication-fundamentals/README.md) |
| 14 | [Kerberoasting Assessment](projects/14-kerberoasting-assessment/README.md) |
| 15 | [AS-REP Roasting Assessment](projects/15-asrep-roasting-assessment/README.md) |

### Intermediate — 16–35
| # | Project |
|---:|---|
| 16 | [BloodHound Active Directory Analysis](projects/16-bloodhound-ad-analysis/README.md) |
| 17 | [SharpHound Data Collection and Analysis](projects/17-sharphound-data-collection/README.md) |
| 18 | [Active Directory ACL Enumeration](projects/18-ad-acl-enumeration/README.md) |
| 19 | [Dangerous ACL and Permission Abuse Assessment](projects/19-dangerous-acl-permission-assessment/README.md) |
| 20 | [Unconstrained Delegation Assessment](projects/20-unconstrained-delegation-assessment/README.md) |
| 21 | [Constrained Delegation Assessment](projects/21-constrained-delegation-assessment/README.md) |
| 22 | [Resource-Based Constrained Delegation Assessment](projects/22-resource-based-constrained-delegation-assessment/README.md) |
| 23 | [Domain Trust Enumeration](projects/23-domain-trust-enumeration/README.md) |
| 24 | [Cross-Domain Trust Security Assessment](projects/24-cross-domain-trust-security-assessment/README.md) |
| 25 | [LAPS and Windows LAPS Security Assessment](projects/25-laps-windows-laps-assessment/README.md) |
| 26 | [Local Administrator Password Reuse Assessment](projects/26-local-admin-password-reuse/README.md) |
| 27 | [Domain Controller Security Assessment](projects/27-domain-controller-security-assessment/README.md) |
| 28 | [Windows Credential Exposure Assessment](projects/28-windows-credential-exposure/README.md) |
| 29 | [Cached Credentials and Credential Hygiene](projects/29-cached-credentials-hygiene/README.md) |
| 30 | [NTLM Authentication Security Assessment](projects/30-ntlm-authentication-assessment/README.md) |
| 31 | [LDAP Signing and Channel Binding Assessment](projects/31-ldap-signing-channel-binding/README.md) |
| 32 | [SMB Signing and Relay Exposure Assessment](projects/32-smb-signing-relay-exposure/README.md) |
| 33 | [Active Directory Certificate Services Enumeration](projects/33-adcs-enumeration/README.md) |
| 34 | [ADCS Misconfiguration Assessment — ESC1](projects/34-adcs-esc1-assessment/README.md) |
| 35 | [ADCS Misconfiguration Assessment — ESC2 and ESC3](projects/35-adcs-esc2-esc3-assessment/README.md) |

### Advanced — 36–50
| # | Project |
|---:|---|
| 36 | [Advanced ADCS Assessment — ESC4 and ESC6](projects/36-adcs-esc4-esc6-assessment/README.md) |
| 37 | [ADCS ESC8 Web Enrollment Assessment](projects/37-adcs-esc8-web-enrollment/README.md) |
| 38 | [DCSync Permission and Replication Rights Assessment](projects/38-dcsync-permission-assessment/README.md) |
| 39 | [Domain Privilege Escalation Attack Path Analysis](projects/39-domain-privilege-escalation-path-analysis/README.md) |
| 40 | [Domain Admin Exposure and Privileged Group Assessment](projects/40-domain-admin-exposure/README.md) |
| 41 | [Lateral Movement Risk Assessment](projects/41-lateral-movement-risk-assessment/README.md) |
| 42 | [Pass-the-Hash and Pass-the-Ticket Exposure Assessment](projects/42-pass-the-hash-ticket-exposure/README.md) |
| 43 | [Golden Ticket and Silver Ticket Security Assessment](projects/43-golden-silver-ticket-risk/README.md) |
| 44 | [Active Directory Persistence Risk Assessment](projects/44-ad-persistence-risk-assessment/README.md) |
| 45 | [Forest and Enterprise Admin Security Assessment](projects/45-forest-enterprise-admin-security/README.md) |
| 46 | [Active Directory Federation Services Assessment](projects/46-adfs-security-assessment/README.md) |
| 47 | [Hybrid Active Directory and Entra ID Security Assessment](projects/47-hybrid-ad-entra-id-assessment/README.md) |
| 48 | [Active Directory Attack Path Automation with Python](projects/48-ad-attack-path-automation-python/README.md) |
| 49 | [Complete Active Directory Red Team Assessment](projects/49-complete-ad-red-team-assessment/README.md) |
| 50 | [Enterprise Active Directory Penetration Testing Report](projects/50-enterprise-ad-pentest-report/README.md) |

## Project format
Each project contains objectives, scope, prerequisites, lab architecture, tool setup, a step-by-step procedure, example commands and expected output, findings and risk analysis, evidence guidance, remediation, and retesting.

Screenshots in this repository are **simulated training illustrations**. They are not captured from a live customer environment and must never be represented as real assessment evidence.

## Progress
- [x] Project 01 — Active Directory Penetration Testing Lab Setup
- [x] Project 02 — Windows Server Domain Controller Installation
- [x] Project 03 — Active Directory Domain and Forest Enumeration
- [x] Project 04 — Domain User and Group Enumeration
- [x] Project 05 — Computer and Server Enumeration
- [x] Project 06 — PowerView Active Directory Enumeration
- [x] Project 07 — LDAP Enumeration and Information Gathering
- [x] Project 08 — SMB Enumeration and Share Assessment
- [x] Project 09 — SYSVOL and NETLOGON Security Assessment
- [x] Project 10 — Group Policy Object (GPO) Security Assessment
- [x] Project 11 — Password Policy and Account Lockout Assessment
- [x] Project 12 — Password Spraying Risk Assessment
- [x] Project 13 — Kerberos Authentication Fundamentals
- [x] Project 14 — Kerberoasting Assessment
- [x] Project 15 — AS-REP Roasting Assessment
- [x] Project 16 — BloodHound Active Directory Analysis
- [x] Project 17 — SharpHound Data Collection and Analysis
- [x] Project 18 — Active Directory ACL Enumeration
- [x] Project 19 — Dangerous ACL and Permission Abuse Assessment
- [x] Project 20 — Unconstrained Delegation Assessment
- [x] Project 21 — Constrained Delegation Assessment
- [x] Project 22 — Resource-Based Constrained Delegation Assessment
- [x] Project 23 — Domain Trust Enumeration
- [x] Project 24 — Cross-Domain Trust Security Assessment
- [x] Project 25 — LAPS and Windows LAPS Security Assessment
- [x] Project 26 — Local Administrator Password Reuse Assessment
- [x] Project 27 — Domain Controller Security Assessment
- [x] Project 28 — Windows Credential Exposure Assessment
- [x] Project 29 — Cached Credentials and Credential Hygiene
- [x] Project 30 — NTLM Authentication Security Assessment
- [x] Project 31 — LDAP Signing and Channel Binding Assessment
- [x] Project 32 — SMB Signing and Relay Exposure Assessment
- [x] Project 33 — Active Directory Certificate Services Enumeration
- [x] Project 34 — ADCS Misconfiguration Assessment — ESC1
- [x] Project 35 — ADCS Misconfiguration Assessment — ESC2 and ESC3
- [x] Project 36 — Advanced ADCS Assessment — ESC4 and ESC6
- [x] Project 37 — ADCS ESC8 Web Enrollment Assessment
- [x] Project 38 — DCSync Permission and Replication Rights Assessment
- [x] Project 39 — Domain Privilege Escalation Attack Path Analysis
- [x] Project 40 — Domain Admin Exposure and Privileged Group Assessment
- [x] Project 41 — Lateral Movement Risk Assessment
- [x] Project 42 — Pass-the-Hash and Pass-the-Ticket Exposure Assessment
- [x] Project 43 — Golden Ticket and Silver Ticket Security Assessment
- [x] Project 44 — Active Directory Persistence Risk Assessment
- [x] Project 45 — Forest and Enterprise Admin Security Assessment
- [x] Project 46 — Active Directory Federation Services Assessment
- [x] Project 47 — Hybrid Active Directory and Entra ID Security Assessment
- [x] Project 48 — Active Directory Attack Path Automation with Python
- [x] Project 49 — Complete Active Directory Red Team Assessment
- [x] Project 50 — Enterprise Active Directory Penetration Testing Report

Start with [Project 01](projects/01-active-directory-lab-setup/README.md), then continue through Projects 02–50.
