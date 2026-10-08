# Oscorp NIST Cybersecurity Framework Assessment

## Project Overview

This project simulates a cybersecurity consulting engagement for **Oscorp**, a fictional organization of approximately 200 employees operating in a predominantly Microsoft cloud environment.

The objective of this engagement is to assess Oscorp's current cybersecurity posture using the **NIST Cybersecurity Framework (NIST CSF)**, identify gaps in existing cybersecurity controls, evaluate the risks associated with those gaps, and develop a risk-based cybersecurity improvement strategy.

The engagement follows the following process:

**Current Environment → NIST CSF Assessment → Key Findings → Risk Assessment & Prioritization → Recommendations → 3-Year Cybersecurity Roadmap → Remediation Tracking**

Selected high-impact risks may also be evaluated using **FAIR (Factor Analysis of Information Risk)** to demonstrate how qualitative cybersecurity findings can be translated into financial risk estimates for business decision-making.

Where appropriate, separate hands-on cybersecurity projects demonstrate the technical implementation or validation of recommended security improvements.

> **Portfolio Note:** Oscorp is a fictional organization used for cybersecurity training and portfolio development. The scenario has been adapted and expanded to integrate governance, risk management, vulnerability management, security hardening, and threat-detection projects into a consistent simulated enterprise environment.

---

## Business Objective

Oscorp has implemented several cybersecurity technologies and operational controls but does not currently maintain a mature enterprise cybersecurity governance and risk management program.

The objectives of this assessment are to:

- Identify existing cybersecurity strengths and deficiencies.
- Evaluate Oscorp's cybersecurity capabilities against the NIST Cybersecurity Framework.
- Consolidate control deficiencies into meaningful cybersecurity risk scenarios.
- Assess and prioritize identified cybersecurity risks based on likelihood and business impact.
- Develop risk-based remediation recommendations.
- Evaluate remediation dependencies, effort, and business value.
- Develop a three-year cybersecurity improvement roadmap.
- Track remediation activities and required validation evidence.
- Demonstrate technical implementation of selected cybersecurity recommendations through supporting hands-on projects.

---

## Oscorp Environment

Oscorp is a fictional organization of approximately **200 employees** operating primarily within a Microsoft cloud environment.

### Technology Environment

| Technology | Purpose |
|---|---|
| Microsoft Azure | Cloud infrastructure |
| Microsoft 365 | Business productivity and cloud services |
| Active Directory | Identity and access management |
| Microsoft Defender | Endpoint protection |
| Tenable Vulnerability Management | Vulnerability scanning and management |
| Palo Alto NGFW | Network security |
| VLANs | Network segmentation |
| VPN | Remote access |
| Windows SOE | Standardized Windows endpoints |
| Horizon Labs | Critical third-party SaaS application |

### Cybersecurity Team

- **Cybersecurity Analyst** — Supports security operations and incident investigation.
- **Network Engineer** — Manages network security and firewall infrastructure.
- **Senior Cybersecurity Consultant** — Conducts the NIST CSF assessment and develops the cybersecurity improvement strategy.

Cybersecurity responsibilities are currently distributed across the IT organization and have not been fully formalized.

---

## Assessment & Risk Management Process

### 1. NIST CSF Assessment

Oscorp's current cybersecurity capabilities are assessed across the five NIST CSF functions:

**Identify → Protect → Detect → Respond → Recover**

Controls are evaluated against the organization's current environment to identify existing capabilities and cybersecurity deficiencies.

### 2. Key Findings

Related control deficiencies are consolidated into meaningful cybersecurity findings rather than treating every failed control as an independent business risk.

Examples include:

- Cybersecurity Governance
- Identity and Access Management
- Vulnerability Management
- Security Monitoring and Detection
- Incident Response
- Third-Party Risk Management
- Data Protection

### 3. Risk Assessment

Major findings are evaluated using a qualitative risk methodology based on:

**Likelihood × Impact = Current Risk Score**

The initial assessment uses a 1–5 scale for likelihood and impact to support consistent risk classification and prioritization.

### 4. Risk Prioritization

Risk severity alone does not determine remediation order.

Remediation priorities also consider:

- Business impact
- Existing controls
- Dependencies
- Implementation effort
- Estimated cost
- Risk reduction
- Technical feasibility

Findings are assigned remediation priorities to support management decision-making and roadmap development.

### 5. Risk Treatment

For each material risk, an appropriate treatment strategy is identified:

**Mitigate | Accept | Transfer | Avoid**

Recommended security improvements are then mapped to the risks they are intended to reduce.

### 6. FAIR Risk Analysis

Selected material cybersecurity risks may undergo additional quantitative analysis using FAIR.

Rather than applying FAIR to every failed NIST CSF control, FAIR is used selectively where financial risk information could improve management decision-making.

### 7. Three-Year Cybersecurity Roadmap

Prioritized remediation initiatives are organized into a three-year improvement roadmap based on risk, dependencies, implementation effort, and business requirements.

### 8. Remediation Tracking

Corrective actions are tracked through an action plan containing remediation owners, milestones, target dates, implementation status, and validation evidence.

After remediation, affected controls can be reassessed to determine whether residual risk has been reduced to an acceptable level.

---

## NIST CSF Assessment Results

The assessment identified several existing cybersecurity strengths as well as significant gaps across the NIST CSF functions.

### Identify

**Strengths**
- Established business strategy and objectives.
- Network and cloud architecture documentation exists.
- Business continuity and disaster recovery capabilities are established.

**Key Gaps**
- No formal cybersecurity risk management process.
- No defined cybersecurity risk appetite or tolerance.
- Cybersecurity roles and responsibilities are not fully formalized.
- No comprehensive information security policy.
- Software, SaaS applications, and third-party systems are not fully inventoried and classified.
- No formal third-party cybersecurity risk management process.
- Cybersecurity threats and business impacts are not formally assessed and documented.

### Protect

**Strengths**
- Active Directory provides centralized identity management.
- Microsoft Defender provides endpoint protection.
- Palo Alto firewalls and VLANs provide network protection and segmentation.
- Physical security controls are established.
- Backups are regularly performed and periodically tested.

**Key Gaps**
- Multi-factor authentication is not implemented.
- Shared privileged administrator credentials exist.
- Privileged Access Management (PAM) is not implemented.
- Least privilege and access reviews are not consistently enforced.
- Data classification and Data Loss Prevention (DLP) are not established.
- Formal change-management processes are not established.
- Vulnerability management has historically been performed on an ad-hoc basis.

### Detect

**Strengths**
- Microsoft Defender provides endpoint security telemetry.
- Tenable provides vulnerability visibility.
- Physical security monitoring is established.

**Key Gaps**
- No centralized SIEM capability.
- Security logs are not centrally aggregated and correlated.
- No formal security-event analysis and prioritization process.
- Detection thresholds and escalation procedures are not formally established.
- Detection capabilities are not routinely tested.
- Detection processes lack formal continuous improvement.

### Respond

**Key Gaps**
- No formal cybersecurity Incident Response Plan.
- Incident response roles and responsibilities are not formally documented.
- Incident severity and escalation criteria are not established.
- Formal containment, mitigation, and eradication procedures are not established.
- No formal digital forensics capability.
- Incident response exercises are not routinely conducted.
- Lessons learned are not formally incorporated into response improvements.

### Recover

**Strengths**
- Documented disaster recovery planning.
- Periodic disaster recovery testing.
- Regular backups and backup testing.
- Established business continuity planning.
- Recovery procedures are periodically reviewed and improved.
- Recovery communication and escalation procedures are established.

### Govern (GV)

**Key Gaps**

- No formal cybersecurity governance framework.
- Cybersecurity risk appetite and tolerance are not formally established.
- Cybersecurity roles, responsibilities, and accountability are not fully documented.
- No comprehensive information security policy.
- Cybersecurity risk management is not consistently integrated into organizational decision-making.
- Third-party cybersecurity risk management lacks formal oversight.

**Recommended Improvements**

- Establish a cybersecurity governance structure with defined accountability.
- Document cybersecurity policies and management responsibilities.
- Define organizational risk appetite and tolerance.
- Establish periodic cybersecurity risk reporting to leadership.
- Integrate supplier cybersecurity risk management into organizational governance.

Overall, Oscorp has established several foundational technical and recovery capabilities but lacks the governance, risk management, identity security, monitoring, and incident response processes required for a mature enterprise cybersecurity program.
