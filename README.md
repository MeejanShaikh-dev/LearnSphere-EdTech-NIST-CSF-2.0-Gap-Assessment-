# LearnSphere EdTech — NIST CSF 2.0 Gap Assessment

### Current State → Target State → Gap Analysis → Risk-Based Remediation

![NIST CSF 2.0](https://img.shields.io/badge/Framework-NIST%20CSF%202.0-blue)
![Project Type](https://img.shields.io/badge/Project-Simulated%20GRC-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Overview

A hands-on **NIST Cybersecurity Framework (CSF) 2.0 Gap Assessment** developed for **LearnSphere EdTech**, a fictional cloud-based EdTech organization providing an LMS to schools.

The organization is assumed to have existing but partially documented and ad-hoc cybersecurity practices. The assessment evaluates the **Current Profile against a defined Target Profile**, identifies security gaps, prioritizes them based on risk and business impact, and develops a practical remediation roadmap.

> **Note:** LearnSphere EdTech is fictional and all assessment data, assumptions, scores and evidence scenarios are created for portfolio and learning purposes.

---

## 🎯 Objectives

- Develop Current and Target Organizational Profiles
- Assess cybersecurity outcomes against NIST CSF 2.0
- Identify and document cybersecurity gaps
- Prioritize gaps using risk and business sensitivity
- Develop an accountable remediation roadmap
- Define KPIs/KRIs for continuous monitoring
- Define evidence required for validation
- Support management-level cybersecurity decision-making

---

## 🧭 NIST CSF 2.0 Functions

| Function | Focus |
|---|---|
| **Govern** | Governance, policies, risk strategy & oversight |
| **Identify** | Assets, data, risks & dependencies |
| **Protect** | IAM, MFA, data protection & security controls |
| **Detect** | Monitoring, logging & detection |
| **Respond** | Incident management & mitigation |
| **Recover** | Recovery, restoration & improvement |

### Reference Material

- NIST CSF 2.0
- NIST SP 1301 — Organizational Profiles
- NIST SP 1302 — CSF Tiers
- ISO/IEC 27001:2022 — contextual reference
- India DPDP Act — regulatory context

---

## 🔬 Assessment Methodology

```text
**Business Context
      ↓
Assessment Scope
      ↓
Current Profile
      ↓
Target Profile
      ↓
Gap Analysis
      ↓
Risk-Based Prioritization
      ↓
Remediation Roadmap
      ↓
KPIs / KRIs
      ↓
Evidence Validation
      ↓
Continuous Improvement

An internal 0–4 scoring model was used to compare Current vs Target states.

The 0–4 model is a project-specific scoring mechanism and is not an official NIST CSF maturity scale.

📊 Executive Results
NIST Function	Current	Target	Gap
Govern	1.75	3.00	1.25
Identify	1.75	3.00	1.25
Protect	1.75	3.25	1.50
Detect	1.75	3.00	1.25
Respond	2.00	3.00	1.00
Recover	1.75	3.00	1.25
Overall	1.79	3.04	1.25

Protect represented the largest functional gap, particularly around student-record access governance.

🚨 Key Findings

The assessment identified 24 prioritized cybersecurity gaps, including:

Children's data governance
Student-data inventory & minimization
Student-record access governance
Privileged access & MFA
Security monitoring and detection
Incident response
Recovery testing
Third-party security oversight
Cybersecurity governance and accountability
Highest-Priority Area

PR.AA-05 — Student-record access governance

Key improvements include:

RBAC
Least privilege
Separation of duties
Recurring access certification
Privileged-access governance
Exception management
🗺️ Remediation Roadmap
0–30 Days — Govern & Contain
Establish children's-data governance ownership
Formalize requirements and consent processes
Review privileged and emergency access
Address excessive data collection
31–90 Days — Define & Implement
Build authoritative data inventory
Implement RBAC / SoD
Strengthen MFA
Establish access certification
Improve retention and disposal
Develop monitoring and incident-response capabilities
91–180 Days — Test, Measure & Improve
Conduct recovery exercises
Validate RTO/RPO
Improve third-party monitoring
Establish security metrics
Perform management review
Reassess Current vs Target Profile
📈 KPIs / KRIs
Metric	Target
Privileged MFA Coverage	100%
Student Data Access Review	100% quarterly
Children's Data Inventory	100% mapped
Security Monitoring Coverage	≥95%
High-Risk Gap Aging	Zero overdue P1
Recovery Test Success	100% planned tests
📂 Evidence Plan

Evidence requirements were defined to validate remediation, including:

Governance: Policies, risk reports, management minutes
Data: Data inventory, data flows, consent and retention records
IAM: IAM exports, RBAC matrix, MFA and access-review evidence
Cloud: AWS configurations and security findings
Monitoring: SIEM sources, alerts and dashboards
Incident Response: Incident register, playbooks and exercises
Recovery: Backup, recovery, RTO/RPO and test evidence
Third Parties: Vendor assessments, contracts and questionnaires

🔗 Relationship to Project 1

This assessment continues the previous LearnSphere ISO/IEC 27001:2022 ISMS project.

Project 1	Used in Project 2
Organizational Context	Business & regulatory context
Asset Register	Asset & information identification
Risk Register	Risk-based prioritization
Statement of Applicability	Existing security treatment context
Internal Audit	Control/evidence context
Corrective Actions & Management Review	Improvement planning

This demonstrates cross-framework GRC traceability rather than treating each framework as an isolated exercise.

📁 Repository Structure
LearnSphere-NIST-CSF-2.0-Gap-Assessment/
│
├── README.md
├── 01_Project_Context/
├── 02_Current_Profile/
├── 03_Target_Profile/
├── 04_Gap_Assessment/
├── 05_Gap_Prioritization/
├── 06_Remediation_Roadmap/
├── 07_KPI_KRI/
├── 08_Evidence_Plan/
├── 09_Executive_Report/
└── 10_Visuals/
💼 Skills Demonstrated

Frameworks: NIST CSF 2.0, NIST SP 1301, NIST SP 1302, ISO/IEC 27001:2022

GRC: Gap Assessment, Risk Management, Risk Prioritization, Remediation Planning, Governance, Compliance, Evidence Management

Security: IAM, MFA, RBAC, Data Protection, Cloud Security, Monitoring, Incident Response, Recovery, Third-Party Risk

Deliverables: Current Profile, Target Profile, Gap Register, Risk Prioritization, Remediation Roadmap, KPI/KRI Register, Evidence Plan and Executive Report

⚠️ Disclaimer

This is a simulated GRC portfolio project. LearnSphere EdTech is fictional, and all scores, assumptions, evidence, gaps, priorities, owners and remediation timelines are illustrative.

This project is not a real audit, certification assessment, compliance opinion or independent assessment.

👤 Author

Meejan Shaikh

GRC Analyst | Information Security | Risk & Compliance | Cybersecurity Governance

GRC is not just about finding gaps — it is about turning gaps into owned, measurable and evidence-based improvements.


### ✅ This is the version I'd use

It's now **compact enough for GitHub**, but it still covers your complete Project 2 lifecycle:

**Context → Scope → NIST CSF → Current Profile → Target Profile → 24 Gaps → Prioritization → Roadmap → KPIs/KRIs → Evidence → Project 1 Traceability → Skills → Disclaimer.**

It also preserves the important distinction that your **0–4 scoring is your internal assessment model, not an official NIST maturity scale**.**
