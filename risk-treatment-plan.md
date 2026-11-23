
# Risk Treatment Plan
## Healthcare Information Security Risk Assessment – Hopewell Medical Centre

**Prepared by:** Oluebube Charity Nwaejike  
**Role:** Cybersecurity GRC Professional  
**Project Type:** Illustrative GRC Portfolio Exercise  
**Assessment Basis:** Fictional healthcare organisation

---

## 1. Introduction

This Risk Treatment Plan outlines the proposed actions for addressing the information security risks identified during the illustrative risk assessment of Hopewell Medical Centre.

The purpose is to reduce information security risks to an acceptable level through appropriate security controls, clear accountability, implementation timelines, and ongoing monitoring.

The plan is based on the risks documented in the project's Risk Register and Risk Analysis and Evaluation.

**Important:** Hopewell Medical Centre is fictional. The treatments, owners, timelines, and target residual risk scores in this document are proposed planning assumptions. They do not represent controls implemented or verified in a real healthcare organisation.

## 2. Risk Treatment Options

The following treatment options are considered:

| Treatment option | Description |
|---|---|
| Mitigate | Reduce the likelihood or impact of a risk by implementing security controls. |
| Avoid | Stop or change an activity that creates an unacceptable risk. |
| Transfer | Share or transfer some financial or operational consequences through mechanisms such as insurance or contractual arrangements. |
| Accept | Formally acknowledge and retain a risk within the organisation's approved risk appetite. |

Risk transfer does not remove the organisation's responsibility for protecting patient and business information.

## 3. Risk Treatment Prioritisation

Treatment priority is based on the initial risk ratings:

- Critical risks: Immediate management attention and priority treatment.
- High risks: Planned remediation with management oversight.
- Moderate risks: Treatment or formal acceptance based on risk appetite.
- Low risks: Monitor and maintain appropriate safeguards.

All treatment decisions should be approved by the appropriate management authority.

## 4. Risk Treatment Action Plan

| Risk ID | Risk description | Initial rating | Treatment strategy | Proposed treatment actions | Responsible risk owner | Target timeline |
|---|---|---|---|---|---|---|
| R001 | Unauthorised disclosure of patient records | Critical | Mitigate | Implement role-based access control (RBAC), enforce MFA, conduct periodic access reviews, and maintain audit logs of patient record access. | Medical Records Manager | 0–30 days |
| R002 | Compromise of staff login credentials | Critical | Mitigate | Enforce strong password requirements, implement MFA, monitor suspicious login activity, and establish account lockout and credential-reset procedures. | IT Manager | 0–30 days |
| R003 | Malware infection due to unpatched systems | High | Mitigate | Establish a patch management programme, deploy endpoint protection, perform vulnerability scans, and maintain an inventory of supported systems. | IT Manager | 0–60 days |
| R004 | Network compromise and lateral movement | High | Mitigate | Implement network segmentation, review firewall rules, restrict unnecessary network access, and monitor network activity. | IT/Network Administrator | 0–60 days |
| R005 | Ransomware attack causing data unavailability | High | Mitigate | Maintain encrypted offline or immutable backups, restrict backup access, establish backup schedules, and conduct periodic restoration tests. | IT Manager | 0–30 days |
| R006 | Excessive staff privileges leading to misuse of patient data | High | Mitigate | Apply least-privilege access, separate conflicting duties, review user permissions, and monitor privileged account activity. | Department Heads and IT Manager | 0–60 days |
| R007 | Unauthorised access to laboratory information | High | Mitigate | Restrict laboratory system access by job role, review permissions, enforce authentication controls, and enable audit logging. | Laboratory Manager | 0–60 days |
| R008 | Phishing attack resulting in employee data or account compromise | High | Mitigate | Conduct regular security awareness training, run simulated phishing exercises, establish a reporting process, and provide guidance on suspicious messages. | HR Manager and GRC Officer | 0–60 days |
| R009 | Unauthorised modification of security policies | Moderate | Mitigate | Introduce document access restrictions, version control, approval workflows, and periodic reviews of security policies. | Management/GRC Officer | 0–90 days |
| R010 | Third-party compromise exposing organisational information | High | Mitigate and partially transfer | Conduct third-party security assessments, include security and data protection requirements in contracts, review provider access, and consider appropriate cyber insurance. | Procurement Manager and IT Manager | 0–90 days |

**Timeline note:** The timelines are proposed periods measured from formal approval of the treatment plan. They are planning targets, not evidence of completed remediation.

## 5. Target Residual Risk

The following scores represent the desired risk levels after the proposed treatments have been implemented and their effectiveness assessed.

| Risk ID | Initial score | Target likelihood | Target impact | Target score | Target rating |
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

**Scoring method:** Likelihood × Impact, using the illustrative 5×5 risk matrix defined in the Risk Register.

These are target scenarios, not verified residual risk ratings. The organisation would need to implement the proposed controls, collect evidence, and reassess each risk before assigning an actual residual rating.

The impact score may remain unchanged where a control mainly reduces the likelihood of an incident rather than the consequences if it occurs.

## 6. Risk Ownership and Accountability

Effective risk treatment requires clear accountability.

- **Risk Owner:** The manager accountable for ensuring that the risk is appropriately managed.
- **Treatment Action Owner:** The individual or team responsible for carrying out a specific remediation activity.
- **GRC Function:** Coordinates risk tracking, monitors treatment progress, maintains documentation, and reports outstanding risks.
- **Senior Management:** Approves significant treatment decisions, allocates resources, and authorises risk acceptance where appropriate.

Risk owners should provide progress updates and supporting evidence to the GRC function.

## 7. Monitoring and Review

The following activities are recommended to monitor the effectiveness of the treatment plan:

1. Track each treatment action against its approved timeline.
2. Maintain evidence of implemented controls.
3. Conduct periodic access reviews and vulnerability assessments.
4. Review backup and restoration test results.
5. Monitor security awareness participation and phishing simulation outcomes.
6. Review third-party security documentation and contractual obligations.
7. Reassess risks after significant changes, incidents, or control failures.
8. Escalate overdue treatment actions and unacceptable risks to management.

The treatment plan should be reviewed at least quarterly as a proposed baseline, or earlier when significant changes occur.

## 8. Risk Acceptance

Where management decides to retain a risk, the decision should be formally documented and approved by an authorised risk owner or management authority.

The acceptance record should include:

- Risk ID and description.
- Business justification for acceptance.
- Existing safeguards and known limitations.
- Residual risk rating.
- Approval authority and approval date.
- Review date or conditions that would trigger reassessment.

Critical and high risks should receive particular scrutiny before acceptance. Risk acceptance should be consistent with the organisation's approved risk appetite and applicable legal and regulatory obligations.

## 9. Conclusion

This Risk Treatment Plan provides a structured approach for addressing the information security risks identified at the fictional Hopewell Medical Centre.

By assigning accountability, proposing practical security controls, setting treatment timelines, and defining monitoring activities, the organisation can work towards reducing its exposure to information security threats.

The effectiveness of the plan will depend on management commitment, adequate resources, implementation of appropriate controls, and continuous risk monitoring.

---

## Disclaimer

This document is an illustrative cybersecurity GRC portfolio project developed for demonstration and learning purposes. Hopewell Medical Centre is fictional. No real organisational assessment, control implementation, management approval, or independent validation has been performed.

The proposed controls, treatment owners, timelines, and target residual risk ratings are hypothetical and should be tailored and validated before use in a real organisation.
