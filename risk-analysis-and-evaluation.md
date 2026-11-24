
# Risk Analysis and Evaluation
## Healthcare Information Security Risk Assessment – Hopewell Medical Centre

**Prepared by:** Oluebube Charity Nwaejike  
**Professional Focus:** Cybersecurity Governance, Risk and Compliance  
**Project Type:** Illustrative GRC Portfolio Exercise  
**Organisation:** Hopewell Medical Centre (Fictional)

---

## 1. Introduction

This document presents the analysis and evaluation of information security risks identified during the illustrative assessment of Hopewell Medical Centre.

The objective is to determine the severity of identified risks, establish priorities, and provide a basis for management decisions regarding risk treatment.

All scenarios, ratings, and proposed controls are illustrative and have not been validated through an actual organisational audit.

## 2. Risk Analysis Methodology

The assessment uses a qualitative 5 × 5 risk matrix.

**Risk Score = Likelihood × Impact**

### 2.1 Likelihood Scale

| Rating | Description |
|---|---|
| 1 | Rare |
| 2 | Unlikely |
| 3 | Possible |
| 4 | Likely |
| 5 | Almost Certain |

### 2.2 Impact Scale

| Rating | Description |
|---|---|
| 1 | Insignificant |
| 2 | Minor |
| 3 | Moderate |
| 4 | Major |
| 5 | Severe |

### 2.3 Risk Classification

| Score | Classification |
|---|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

These scoring thresholds are illustrative project-specific criteria and are not universal requirements prescribed by ISO standards.

## 3. Inherent Risk Analysis

Inherent risk represents the level of exposure before considering the effectiveness of security controls.

The following table presents the initial risk ratings identified in the Risk Register.

| Risk ID | Risk Description | Likelihood | Impact | Inherent Score | Rating |
|---|---|---:|---:|---:|---|
| R001 | Unauthorised disclosure of patient records | 4 | 5 | 20 | Critical |
| R002 | Compromise of staff login credentials | 4 | 5 | 20 | Critical |
| R003 | Malware infection due to unpatched systems | 4 | 4 | 16 | High |
| R004 | Network compromise and lateral movement | 3 | 5 | 15 | High |
| R005 | Ransomware causing data unavailability | 3 | 5 | 15 | High |
| R006 | Insider misuse of excessive privileges | 3 | 4 | 12 | High |
| R007 | Unauthorised access to laboratory records | 3 | 4 | 12 | High |
| R008 | Phishing and employee account compromise | 4 | 3 | 12 | High |
| R009 | Unauthorised modification of security documentation | 2 | 3 | 6 | Moderate |
| R010 | Third-party security compromise | 3 | 5 | 15 | High |

## 4. Control Assessment

The effectiveness of existing controls has not been independently established.

The following safeguards are proposed for implementation or validation:

| Risk ID | Proposed Security Controls |
|---|---|
| R001 | Role-Based Access Control (RBAC), MFA and periodic access reviews |
| R002 | MFA, strong password policies and account monitoring |
| R003 | Patch management, endpoint protection and vulnerability scanning |
| R004 | Network segmentation, firewalls and network monitoring |
| R005 | Offline backups, encryption and regular restoration testing |
| R006 | Least privilege, segregation of duties and user activity monitoring |
| R007 | Departmental access restrictions and audit logging |
| R008 | Security awareness training and phishing simulations |
| R009 | Document access restrictions and version control |
| R010 | Third-party security assessments and contractual security requirements |

These are proposed controls, not verified existing safeguards.

## 5. Residual Risk Assessment

Residual risk represents the level of risk remaining after controls have been implemented and their effectiveness assessed.

For this exercise, the following scores represent hypothetical target scenarios assuming the proposed controls are implemented and operate effectively.

| Risk ID | Inherent Score | Target Likelihood | Target Impact | Target Residual Score | Target Rating |
|---|---:|---:|---:|---:|---|
| R001 | 20 | 2 | 5 | 10 | High |
| R002 | 20 | 2 | 5 | 10 | High |
| R003 | 16 | 2 | 4 | 8 | Moderate |
| R004 | 15 | 2 | 5 | 10 | High |
| R005 | 15 | 2 | 5 | 10 | High |
| R006 | 12 | 2 | 4 | 8 | Moderate |
| R007 | 12 | 2 | 4 | 8 | Moderate |
| R008 | 12 | 2 | 3 | 6 | Moderate |
| R009 | 6 | 1 | 3 | 3 | Low |
| R010 | 15 | 2 | 5 | 10 | High |

**Important:** These are illustrative target ratings, not verified current residual risks. Actual residual risk must be reassessed using evidence of control implementation and operating effectiveness.

The impact score may remain unchanged where proposed controls primarily reduce the likelihood of an incident rather than its consequences.

## 6. Risk Evaluation and Prioritisation

Based on the initial risk assessment, the following priorities have been established.

### 6.1 Critical Risks

- **R001:** Unauthorised disclosure of patient records.
- **R002:** Compromise of staff login credentials.

These risks require urgent management attention and priority treatment because of their potential consequences for patient confidentiality and organisational operations.

### 6.2 High Risks

- **R003:** Malware infection.
- **R004:** Network compromise.
- **R005:** Ransomware and data unavailability.
- **R006:** Insider misuse of excessive privileges.
- **R007:** Laboratory records exposure.
- **R008:** Phishing and employee account compromise.
- **R010:** Third-party security compromise.

These risks require documented treatment decisions, assigned ownership and appropriate management oversight.

### 6.3 Moderate Risk

- **R009:** Unauthorised modification of security documentation.

This risk requires proportionate controls, appropriate governance and periodic monitoring.

## 7. Risk Acceptance Considerations

Management should establish formal risk acceptance criteria and designate authorised risk owners.

Critical and High risks should receive particular scrutiny before acceptance.

Any decision to accept a risk should include:

- Documented business justification.
- Identified risk owner.
- Current risk rating.
- Existing safeguards and known limitations.
- Management approval.
- Review date or reassessment conditions.

Residual risks should be compared against the organisation's approved risk appetite and tolerance.

## 8. Recommendations

The following actions are recommended:

- Prioritise protection of patient medical records.
- Implement and validate Multi-Factor Authentication.
- Strengthen patch and vulnerability management.
- Improve backup protection and recovery testing.
- Conduct periodic user access reviews.
- Establish third-party security oversight.
- Maintain a formal risk monitoring and reporting process.

## 9. Conclusion

This analysis demonstrates how inherent and residual risk assessments support informed cybersecurity risk management.

The findings provide management with a structured basis for prioritising security investments, implementing appropriate controls and improving organisational resilience.

Effective risk management requires continuous monitoring, management commitment and periodic reassessment of identified risks.

---

## Disclaimer

This is an illustrative cybersecurity GRC portfolio project developed for professional demonstration and development purposes.

Hopewell Medical Centre is fictional. No actual organisational audit, technical testing, stakeholder interviews, control validation or management approval was performed.

All assets, risks, scores, proposed controls and target residual ratings are hypothetical assumptions.

This project does not constitute evidence of ISO/IEC 27001 certification or compliance by any real organisation.
