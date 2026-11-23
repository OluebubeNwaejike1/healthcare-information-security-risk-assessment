Risk Analysis and Evaluation – Hopewell Medical Centre

1. Introduction

This document presents the analysis and evaluation of information security risks identified during the assessment of Hopewell Medical Centre.

The objective is to determine the severity of identified risks, establish priorities and provide a basis for management decisions regarding risk treatment.

All scenarios and ratings are illustrative and have not been validated through an actual organisational audit.

2. Risk Analysis Methodology

The assessment uses a qualitative 5 × 5 risk matrix.

Risk Score = Likelihood × Impact.

Likelihood

Rating| Description
1| Rare
2| Unlikely
3| Possible
4| Likely
5| Almost Certain

Impact

Rating| Description
1| Insignificant
2| Minor
3| Moderate
4| Major
5| Severe

Risk Rating

Score| Classification
1–4| Low
5–9| Moderate
10–16| High
17–25| Critical

3. Inherent Risk Analysis

Inherent risk represents the level of exposure before considering the effectiveness of security controls.

Risk ID| Risk Description| Likelihood| Impact| Inherent Score| Rating
R001| Unauthorized access to patient medical records| 4| 5| 20| Critical
R002| Compromise of staff login credentials| 4| 5| 20| Critical
R003| Malware infection due to unpatched systems| 4| 4| 16| High
R004| Unauthorized network access| 3| 5| 15| High
R005| Backup compromise through ransomware| 3| 5| 15| High
R006| Insider misuse of excessive privileges| 3| 4| 12| High
R007| Unauthorized access to laboratory records| 3| 4| 12| High
R008| Phishing and employee account compromise| 4| 3| 12| High
R009| Unauthorized modification of security documentation| 2| 3| 6| Moderate
R010| Third-party security compromise| 3| 5| 15| High

4. Control Assessment

The effectiveness of existing controls has not been independently established.

The following safeguards are proposed for validation:

Risk ID| Proposed Security Controls
R001| Role-Based Access Control, MFA and access reviews
R002| MFA, strong password policies and account monitoring
R003| Patch management, endpoint protection and vulnerability scanning
R004| Network segmentation, firewalls and network monitoring
R005| Offline backups, encryption and regular restoration testing
R006| Least privilege, segregation of duties and user activity monitoring
R007| Departmental access restrictions and audit logging
R008| Security awareness training and phishing simulations
R009| Document access restrictions and version control
R010| Third-party security assessments and contractual security requirements

5. Residual Risk Assessment

Residual risk is the level of risk remaining after existing controls have been implemented and their effectiveness assessed.

For this exercise, the following residual scores are hypothetical target scenarios assuming the proposed controls are implemented and operate effectively.

Risk ID| Inherent Score| Target Residual Likelihood| Target Residual Impact| Target Residual Score| Target Rating
R001| 20| 2| 5| 10| High
R002| 20| 2| 5| 10| High
R003| 16| 2| 4| 8| Moderate
R004| 15| 2| 5| 10| High
R005| 15| 2| 5| 10| High
R006| 12| 2| 4| 8| Moderate
R007| 12| 2| 4| 8| Moderate
R008| 12| 2| 3| 6| Moderate
R009| 6| 1| 3| 3| Low
R010| 15| 2| 5| 10| High

Important: These are illustrative target ratings, not verified current residual risks. Actual residual risk must be reassessed using evidence of control implementation and operating effectiveness.

6. Risk Evaluation and Prioritisation

The assessment identifies the following priorities:

Critical inherent risks

- R001: Patient medical records exposure.
- R002: Staff credential compromise.

These require urgent management attention.

High inherent risks

- R003: Malware infection.
- R004: Network intrusion.
- R005: Backup compromise.
- R006: Insider misuse.
- R007: Laboratory records exposure.
- R008: Phishing attacks.
- R010: Third-party compromise.

These require documented treatment decisions and appropriate oversight.

Moderate inherent risk

- R009: Security documentation modification.

This requires proportionate controls and periodic monitoring.

7. Risk Acceptance Considerations

Management should establish formal risk acceptance criteria and designate authorised risk owners.

Critical risks should not be accepted without documented management review and justification.

Residual risks should be compared against approved organisational risk appetite and tolerance.

8. Recommendations

1. Prioritise protection of patient medical records.
2. Implement and validate multi-factor authentication.
3. Strengthen patch and vulnerability management.
4. Improve backup protection and recovery testing.
5. Conduct periodic access reviews.
6. Establish third-party security oversight.
7. Maintain a formal risk monitoring and reporting process.

9. Conclusion

The analysis demonstrates how inherent and residual risk assessments support informed cybersecurity risk management.

The findings provide management with a structured basis for prioritising security investments, implementing appropriate controls and improving organisational resilience.

---

Organisation: Hopewell Medical Centre (Fictional)
Project: Healthcare Information Security Risk Assessment
Prepared by: Oluebube Charity Nwaejike
Professional Focus: Cybersecurity Governance, Risk and Compliance
