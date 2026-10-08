# Oscorp | NIST CSF 2.0 Cybersecurity Risk Assessment

**Targeted Cybersecurity Risk Assessment & Three-Year Security Improvement Strategy**

**Framework:** NIST Cybersecurity Framework (CSF) 2.0  
**Assessment Type:** Risk-Based Cybersecurity Gap Assessment  
**Organization:** Oscorp (Fictional Enterprise)  
**Environment:** Microsoft Azure, Microsoft 365, Active Directory, Microsoft Defender, Tenable, Palo Alto NGFW  
**Assessment Method:** Qualitative Risk Assessment — Likelihood × Impact

---

## 1. Executive Summary

This project simulates a cybersecurity consulting engagement for **Oscorp**, a fictional organization of approximately 200 employees operating primarily within a Microsoft cloud environment.

The objective is to evaluate Oscorp's cybersecurity posture using a targeted assessment aligned with the **NIST Cybersecurity Framework (CSF) 2.0**, identify material control deficiencies, assess associated business risks, and develop a prioritized cybersecurity improvement strategy.

Oscorp has established several foundational security capabilities, including endpoint protection, vulnerability scanning, network segmentation, and disaster recovery. However, significant deficiencies remain in identity and privileged access management, security monitoring, incident response, governance, third-party risk management, and data protection.

The assessment consolidates these deficiencies into **seven cybersecurity risk scenarios**, evaluated using a qualitative likelihood and impact methodology.

### Assessment Workflow

**Current Environment → CSF 2.0 Control Assessment → Gap Identification → Risk Analysis → Risk Prioritization → Recommended Controls → Three-Year Roadmap → Remediation Tracking**

The project demonstrates how cybersecurity framework outcomes can be translated into actionable business risk decisions and practical security improvements.

> **Portfolio Disclaimer:** Oscorp is a fictional organization used for cybersecurity training and portfolio development. Findings, assessments, and recommendations are based on a simulated enterprise environment and documented scenario assumptions. This project does not represent an audit or security assessment of an actual organization.

---

## 2. Business Objectives

The assessment is designed to:

- Evaluate existing cybersecurity capabilities against selected NIST CSF 2.0 outcomes.
- Identify control weaknesses and gaps affecting business operations.
- Consolidate related deficiencies into meaningful cybersecurity risk scenarios.
- Assess likelihood and business impact using a consistent risk methodology.
- Prioritize risks based on exposure, potential business consequences, and remediation feasibility.
- Recommend practical and risk-based security improvements.
- Develop a proposed three-year cybersecurity improvement roadmap.
- Define remediation ownership, milestones, and verification requirements.
- Demonstrate the application of cybersecurity governance, risk management, and technical security principles.

---

## 3. Organizational Environment

### Technology Environment

Oscorp operates a predominantly Microsoft-based enterprise environment supporting approximately 200 employees.

| Technology | Primary Function |
|---|---|
| Microsoft Azure | Cloud infrastructure |
| Microsoft 365 | Productivity and cloud services |
| Active Directory | Identity and access management |
| Microsoft Defender | Endpoint protection and security telemetry |
| Tenable Vulnerability Management | Vulnerability identification and assessment |
| Palo Alto NGFW | Network security and traffic control |
| VLANs | Network segmentation |
| VPN | Remote access |
| Windows Standard Operating Environment | Standardized endpoint configuration |
| Horizon Labs | Critical third-party SaaS application |

### Cybersecurity Team

- **Cybersecurity Analyst:** Security operations and incident investigation.
- **Network Engineer:** Network security, infrastructure, and firewall administration.
- **Senior Cybersecurity Consultant:** Assessment, risk analysis, and improvement strategy.

Cybersecurity responsibilities are distributed across the IT organization and are not fully formalized.

---

## 4. Assessment Scope & Methodology

### 4.1 Assessment Framework

The engagement applies a targeted, risk-based assessment aligned with the six functions of **NIST CSF 2.0**:

**Govern → Identify → Protect → Detect → Respond → Recover**

Rather than performing an exhaustive assessment of all CSF 2.0 subcategories, the engagement focuses on selected cybersecurity outcomes relevant to Oscorp's identified security weaknesses and business risks.

Related framework outcomes are grouped into practical assessment questions, allowing the evaluation to emphasize material control deficiencies and their business consequences.

### 4.2 Assessment Focus Areas

The assessment concentrates on seven cybersecurity risk domains:

1. Cybersecurity Governance & Risk Management
2. Identity & Privileged Access Management
3. Vulnerability Management
4. Security Monitoring & Detection
5. Incident Response
6. Third-Party Cybersecurity Risk Management
7. Data Protection & Classification

These domains represent the engagement's assessment focus areas and are not intended to replace the official NIST CSF 2.0 categories.

### 4.3 Assessment Process

The methodology follows five stages:

**Stage 1 — Current-State Review**

Review the simulated organizational environment, documented capabilities, and existing cybersecurity controls.

**Stage 2 — Control Assessment**

Evaluate selected cybersecurity control outcomes against the available scenario information. Identify implemented capabilities, control deficiencies, and areas requiring additional validation.

**Stage 3 — Gap Consolidation**

Group related control deficiencies into cybersecurity findings rather than treating every individual failed control as a separate business risk.

**Stage 4 — Risk Analysis**

Develop risk scenarios describing how identified deficiencies could affect Oscorp's systems, information, and business operations.

**Stage 5 — Risk Treatment & Improvement Planning**

Recommend security improvements, prioritize remediation, and develop a proposed implementation roadmap.

### 4.4 Assessment Scope & Limitations

This is a **targeted NIST CSF 2.0-aligned assessment**, not a comprehensive evaluation of every framework category and subcategory.

The following limitations apply:

- The organization and assessment environment are fictional.
- Findings are based on defined scenario information and assumptions rather than direct production-system access.
- The assessment focuses on selected cybersecurity outcomes and material risk domains.
- Unassessed controls are not assumed to be implemented or deficient.
- Control effectiveness has not been independently verified through a real-world audit.
- Recommendations, implementation timelines, and ownership assignments represent proposed actions rather than approved organizational commitments.

These limitations establish the boundaries of the assessment and prevent unsupported conclusions about Oscorp's overall framework compliance or cybersecurity maturity.

---

## 5. NIST CSF 2.0 Assessment Findings

The targeted assessment identified existing cybersecurity strengths and material control deficiencies across the framework's six functions.

### 5.1 Govern (GV)

**Existing Capabilities**
- Established business objectives and organizational strategy.
- Existing cybersecurity and IT personnel.

**Key Deficiencies**
- No formal cybersecurity risk management process.
- Risk appetite and tolerance are not defined.
- Cybersecurity roles and accountability are not fully documented.
- No comprehensive information security policy.
- Cybersecurity risk management is not consistently integrated into organizational decision-making.
- Third-party cybersecurity risk management lacks formal oversight.

**Related Risks:** R-01, R-06

### 5.2 Identify (ID)

**Existing Capabilities**
- Documented network and cloud architecture.
- Established business strategy and objectives.
- Existing technology and infrastructure visibility.

**Key Deficiencies**
- Software, SaaS applications, and third-party systems are not fully inventoried and classified.
- Assets and services are not consistently prioritized by business criticality.
- Cybersecurity threats and business impacts are not formally assessed and documented.

**Related Risks:** R-01, R-03, R-06, R-07

### 5.3 Protect (PR)

**Existing Capabilities**
- Centralized identity management through Active Directory.
- Microsoft Defender endpoint protection.
- Palo Alto firewalls and network segmentation.
- Established physical security controls.
- Regular backups and periodic backup testing.

**Key Deficiencies**
- Multi-factor authentication is not implemented.
- Shared privileged administrator credentials exist.
- Privileged Access Management is not established.
- Least privilege and access reviews are not consistently enforced.
- Data classification and Data Loss Prevention controls are not established.
- Formal change management requires improvement.

**Related Risks:** R-02, R-07

### 5.4 Detect (DE)

**Existing Capabilities**
- Microsoft Defender endpoint telemetry and alerts.
- Tenable vulnerability visibility.
- Physical security monitoring.

**Key Deficiencies**
- No centralized SIEM capability.
- Security logs are not centrally aggregated and correlated.
- Security-event analysis and prioritization procedures are not formally established.
- Detection thresholds and escalation procedures require improvement.
- Detection capabilities are not routinely tested.

**Related Risks:** R-04

### 5.5 Respond (RS)

**Existing Capabilities**
- Cybersecurity and IT personnel are available to respond to technical issues.
- Microsoft Defender provides security alerts.
- Business continuity and recovery capabilities exist.

**Key Deficiencies**
- No formal cybersecurity incident response plan.
- Incident-response roles and responsibilities are not fully documented.
- Incident severity and escalation criteria are not established.
- Formal containment, eradication, and evidence-handling procedures are not established.
- Incident response exercises are not routinely conducted.
- Lessons learned are not systematically incorporated into response improvements.

**Related Risks:** R-05

### 5.6 Recover (RC)

**Existing Capabilities**
- Documented disaster recovery planning.
- Periodic disaster recovery testing.
- Regular backups and backup validation.
- Established business continuity planning.
- Recovery communication and escalation procedures.

**Assessment Observation**

Recovery capabilities represent an existing organizational strength. However, the effectiveness of these capabilities during a major cybersecurity incident has not been independently validated as part of this simulated engagement.

---

## 6. Cybersecurity Risk Assessment

### 6.1 Risk Scoring Methodology

Identified cybersecurity risks are evaluated using a qualitative likelihood and impact methodology.

**Current Risk Score = Likelihood × Impact**

Both likelihood and impact are evaluated on a scale of 1–5.

- **Likelihood:** The estimated probability of the risk scenario occurring, considering the threat environment, identified deficiencies, and existing controls.
- **Impact:** The potential consequences for business operations, information security, financial performance, and organizational objectives.

The resulting score ranges from **1 to 25**.

### 6.2 Risk Rating Criteria

The following qualitative thresholds are defined for this simulated assessment:

| Current Risk Score | Risk Rating |
|---|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

These thresholds are project-defined and are not prescribed by NIST CSF 2.0.

### 6.3 Risk Register Summary

| Risk ID | Risk Domain | Likelihood | Impact | Current Score | Rating | Priority |
|---|---|---:|---:|---:|---|---|
| R-02 | Identity & Privileged Access | 4 | 4 | 16/25 | High | P1 |
| R-04 | Security Monitoring & Detection | 4 | 4 | 16/25 | High | P1 |
| R-05 | Incident Response | 4 | 4 | 16/25 | High | P1 |
| R-03 | Vulnerability Management | 3 | 4 | 12/25 | High | P2 |
| R-07 | Data Protection & Classification | 3 | 4 | 12/25 | High | P2 |
| R-06 | Third-Party Cybersecurity Risk | 3 | 4 | 12/25 | High | P2 |
| R-01 | Governance & Risk Management | 3 | 3 | 9/25 | Moderate | P3 |

**Risk Treatment:** Mitigate is the proposed treatment strategy for all seven identified risk scenarios.

### 6.4 Risk Prioritization Methodology

Remediation priority is determined using more than the numerical risk score.

Prioritization considers:

- Current risk exposure and potential business impact.
- Threat likelihood and identified attack paths.
- Existing preventive, detective, and recovery controls.
- The potential for an attacker to exploit or expand access.
- Implementation dependencies and technical feasibility.
- Estimated remediation effort and cost.
- Expected reduction in cybersecurity risk.

**Priority Definitions**

- **P1 — Urgent:** Address high-exposure risks with significant potential for immediate security or operational consequences.
- **P2 — High:** Address material risks through near-term remediation initiatives.
- **P3 — Planned:** Address important structural and program improvements through scheduled remediation.
- **P4 — Lower:** Address lower-urgency improvements as resources and business requirements permit.

Not every priority category must be assigned. This assessment uses P1–P3.

Priorities represent recommended remediation urgency, not a claim that the corresponding risks are certain to occur.

### 6.5 Risk Prioritization Rationale

**P1 — Identity & Privileged Access (R-02)**

The absence of MFA, shared privileged credentials, and inconsistent access reviews creates direct opportunities for unauthorized access and privilege misuse. Strengthening authentication and privileged access controls can reduce immediate exposure.

**P1 — Security Monitoring & Detection (R-04)**

Limited centralized monitoring and security-log correlation can delay the identification of malicious activity, potentially increasing attacker dwell time and the scope of compromise. Early improvements should focus on critical log sources, alert prioritization, and escalation before broader SIEM deployment.

**P1 — Incident Response (R-05)**

Without formal incident-response procedures, an otherwise containable incident may escalate due to delayed decision-making and unclear responsibilities. Establishing an incident-response plan, ownership, and initial playbooks provides near-term risk reduction.

**P2 — Vulnerability Management (R-03)**

Tenable provides existing vulnerability visibility, but inconsistent scanning and remediation processes may allow exploitable vulnerabilities to remain unresolved. Formal remediation SLAs and risk-based prioritization should be established.

**P2 — Data Protection & Classification (R-07)**

The absence of consistent data classification and DLP controls increases the potential for inappropriate information handling and disclosure. Initial remediation should identify sensitive information and establish appropriate handling requirements.

**P2 — Third-Party Cybersecurity Risk (R-06)**

Oscorp relies on critical external services, including Horizon Labs, but lacks a formal supplier cybersecurity risk management process. Supplier criticality assessments and due diligence are needed to improve visibility and reduce unmanaged exposure.

**P3 — Governance & Risk Management (R-01)**

Governance deficiencies affect long-term risk ownership, policy consistency, and management oversight. Although this risk has a lower immediate exposure score than the technical risks, foundational governance actions should begin alongside P1 remediation to establish accountability and support sustainable improvements.

---

## 7. Recommended Cybersecurity Improvements

The assessment recommends a risk-based security improvement program focused on reducing exposure and strengthening operational capabilities.

| Risk ID | Recommended Improvements |
|---|---|
| R-02 | Implement MFA, eliminate shared administrator credentials, enforce least privilege, and establish privileged-access reviews. |
| R-04 | Centralize critical security logs, establish alert triage, define escalation procedures, and implement SIEM capabilities. |
| R-05 | Develop an incident-response plan, assign responsibilities, create incident playbooks, and conduct tabletop exercises. |
| R-03 | Establish recurring authenticated scans, remediation SLAs, risk-based prioritization, and verification procedures. |
| R-07 | Develop data-classification standards, establish handling requirements, and implement appropriate information-protection controls. |
| R-06 | Establish supplier inventories, criticality classifications, security due diligence, and recurring supplier assessments. |
| R-01 | Define risk ownership, establish risk appetite, approve security policies, and introduce periodic management oversight. |

---

## 8. Proposed Three-Year Cybersecurity Improvement Strategy

The proposed roadmap organizes security improvements into three implementation phases.

### Year 1 — Immediate Risk Reduction & Foundational Controls

**Primary Focus:** Reduce high-priority exposure and establish essential security processes.

Proposed initiatives:

- Implement MFA and strengthen privileged account security.
- Establish critical security-log collection and alert escalation.
- Develop and approve an incident-response plan.
- Establish vulnerability remediation SLAs and recurring scanning.
- Assign cybersecurity risk owners and establish a basic risk register.
- Initiate critical supplier reviews and identify sensitive data.

### Year 2 — Security Capability Development

**Primary Focus:** Strengthen detection, prevention, and repeatable security operations.

Proposed initiatives:

- Expand SIEM coverage and detection engineering.
- Implement additional privileged access management controls.
- Mature vulnerability management reporting and remediation verification.
- Expand supplier due diligence and ongoing monitoring.
- Implement data classification and appropriate DLP capabilities.
- Conduct incident-response tabletop exercises.

### Year 3 — Program Optimization & Continuous Improvement

**Primary Focus:** Validate control effectiveness and improve cybersecurity program maturity.

Proposed initiatives:

- Optimize security monitoring and detection coverage.
- Establish recurring security-control effectiveness reviews.
- Mature cybersecurity governance and management reporting.
- Improve supplier risk monitoring and reassessment.
- Refine incident response procedures through testing and lessons learned.
- Reassess cybersecurity risks and update remediation priorities.

The roadmap represents a proposed implementation strategy. Actual sequencing would depend on approved budgets, technical dependencies, business requirements, and reassessment of risk.

---

## 9. Remediation Tracking & Validation

Recommended improvements should be managed through a remediation action plan containing:

- Risk and finding reference.
- Corrective action.
- Assigned owner.
- Priority.
- Target completion date.
- Implementation status.
- Dependencies.
- Required validation evidence.
- Residual risk reassessment.

Examples of validation evidence include MFA configuration records, access-review results, vulnerability rescan reports, incident-response exercise records, and security monitoring test results.

Completion of a remediation action should be supported by evidence demonstrating that the intended control has been implemented and is operating as expected.

---

## 10. Supporting Technical Projects

Selected technical portfolio projects may be used to demonstrate implementation and validation of recommended cybersecurity improvements.

**Vulnerability Management**

A hands-on vulnerability management project demonstrates the identification, prioritization, remediation, and verification of vulnerabilities using Tenable and Windows security hardening.

**Security Monitoring & Threat Hunting**

A separate security operations project demonstrates investigation and threat-hunting techniques using Microsoft Defender, Microsoft Sentinel, and KQL.

These supporting projects are distinct from the simulated Oscorp organizational assessment and do not independently validate the fictional organization's actual security posture.

---

## 11. Project Deliverables

The following deliverables support the simulated engagement:

| Deliverable | Purpose |
|---|---|
| NIST CSF 2.0 Assessment Workbook | Documents selected control assessment questions, current-state observations, and identified deficiencies. |
| Detailed Cybersecurity Risk Analysis | Documents seven risk scenarios, existing controls, likelihood and impact rationale, and recommended treatment. |
| Cybersecurity Risk Register | Consolidates risk scores, severity ratings, remediation priorities, and treatment recommendations. |
| Risk Matrix | Visualizes assessed likelihood and impact levels. |
| Three-Year Cybersecurity Roadmap | Presents proposed remediation sequencing and strategic improvement initiatives. |
| Remediation Action Plan | Tracks recommended actions, ownership, milestones, and validation requirements. |

Supporting deliverables are published as part of the repository as they are finalized.

---

## 12. Conclusion

The targeted NIST CSF 2.0 assessment identified material cybersecurity weaknesses affecting Oscorp's ability to prevent unauthorized access, detect malicious activity, respond effectively to incidents, and consistently manage cybersecurity risk.

Although the organization has established technical security and disaster recovery capabilities, improvements are required to reduce current exposure and strengthen cybersecurity governance and operational resilience.

The assessment demonstrates a structured approach to translating cybersecurity control deficiencies into business risk scenarios, evaluating likelihood and impact, prioritizing remediation, and developing a practical cybersecurity improvement strategy.

**The primary objective is to demonstrate the application of cybersecurity risk assessment, GRC methodology, and security improvement planning in a simulated enterprise consulting engagement.**

---

## References

- [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework)
- [NIST CSF 2.0 Reference Tool](https://csrc.nist.gov/Projects/cybersecurity-framework/Filters#/csf/filters)
- [FAIR Institute](https://www.fairinstitute.org/) — Optional quantitative risk analysis reference
