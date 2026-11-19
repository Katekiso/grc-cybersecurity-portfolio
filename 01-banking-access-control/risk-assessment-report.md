# Banking Access Control Risk Assessment Report

**Organization:** ABC Commercial Bank (Fictional)  
**Assessment Type:** Cybersecurity Governance, Risk and Compliance (GRC)  
**Framework:** NIST Cybersecurity Framework (CSF) 2.0  
**Assessment Focus:** Identity Management and Access Control

## 1. Executive Summary

This assessment evaluates access control risks within the simulated ABC Commercial Bank environment. The assessment identified weaknesses in employee access privileges, account deactivation, periodic access reviews and access approval documentation.

These weaknesses could expose sensitive customer information and financial systems to unauthorized access, data breaches and fraudulent activities.

Four cybersecurity risks were identified, with one rated Critical and three rated High under the assessment's defined scoring methodology.

The assessment recommends strengthening identity and access management practices through least privilege, role-based access control, timely account deactivation, periodic access reviews and documented access approval procedures.

## 2. Assessment Scope and Methodology

The assessment focused on:

- Customer databases and financial information.
- Employee user accounts and access privileges.
- Core banking systems.
- Access management processes.
- User access approval and review procedures.

A qualitative risk assessment methodology was applied using a five-point likelihood and impact scale.

Risk scores were calculated as:

**Inherent Risk = Likelihood × Impact**

Risk ratings were classified as:

- Low: 1–4
- Moderate: 5–9
- High: 10–16
- Critical: 17–25

The assessment used the fictional organizational scenario and assumed control weaknesses as its basis. No actual system testing or independent audit evidence was available.

## 3. Key Assets Identified

Seven key assets were documented in the asset inventory, including:

- Customer database.
- Core banking system.
- Employee user accounts.
- Access management system.
- Transaction records.
- Employee workstations.
- Security audit logs.

Customer information, transaction records and banking applications were classified as Confidential due to their sensitivity and business importance.

## 4. Identified Risks and Assessment Results

Four significant access control risks were identified.

| Risk ID | Risk Description | Inherent Score | Rating |
|---|---|---:|---|
| R001 | Excessive employee access privileges | 20 | Critical |
| R002 | Former employees retain active accounts | 15 | High |
| R003 | Failure to conduct periodic access reviews | 16 | High |
| R004 | Insufficient access approval documentation | 12 | High |

R001 represents the highest-priority risk because excessive privileges could enable unauthorized access to sensitive banking information and financial systems.

## 5. Control Gap Analysis

The assessment identified weaknesses in four key security controls:

**C001 – Least Privilege:** Employee permissions are not adequately restricted to job responsibilities.

**C002 – Account Deactivation:** Existing offboarding procedures do not consistently ensure timely removal of former employees' access.

**C003 – Periodic Access Reviews:** The organization lacks an effective periodic process for reviewing employee access privileges.

**C004 – Access Approval:** Access requests and management approvals are not sufficiently documented.

These weaknesses indicate the need for stronger identity and access management governance.

## 6. NIST CSF 2.0 Alignment

The identified risks were mapped to relevant NIST CSF 2.0 subcategories:

- **PR.AA-01:** Identity and credential management, including the management of access and revocation.
- **PR.AA-05:** Access permissions, authorizations and entitlements are defined, managed and reviewed in accordance with least privilege and separation of duties.

These mappings support improvements in identity management and access control governance.

## 7. Risk Treatment Recommendations

The following actions are recommended:

1. Implement role-based access control and enforce least privilege.
2. Establish formal employee offboarding procedures to ensure timely account deactivation.
3. Conduct quarterly user access reviews and retain documented evidence.
4. Introduce formal access request and management approval procedures.
5. Maintain access review records and monitor privileged accounts.

IT Security should coordinate implementation with Human Resources, IT Management and relevant business owners.

## 8. Residual Risk Assessment

Residual risk represents the risk expected to remain after recommended controls have been implemented and operate effectively.

The following are preliminary projected scores, not verified post-implementation results.

| Risk ID | Projected Likelihood | Impact | Residual Score | Rating |
|---|---:|---:|---:|---|
| R001 | 2 | 5 | 10 | High |
| R002 | 1 | 5 | 5 | Moderate |
| R003 | 2 | 4 | 8 | Moderate |
| R004 | 2 | 4 | 8 | Moderate |

The projected scores indicate that the recommended controls could reduce the likelihood of unauthorized access. However, significant consequences may remain if a security incident occurs.

Management should review and formally accept or further treat any residual risks according to the organization's risk appetite.

## 9. Conclusion

The assessment demonstrates that effective identity and access management is essential to protecting customer information and maintaining the security of banking operations.

Implementing least privilege, improving employee offboarding procedures, conducting periodic access reviews and maintaining documented access approvals would strengthen the bank's cybersecurity control environment.

Management should prioritize the Critical and High risks and establish accountability for implementing and monitoring corrective actions.

**Disclaimer:** This assessment is an educational simulation developed for cybersecurity GRC portfolio purposes. ABC Commercial Bank and all associated findings are fictional.
