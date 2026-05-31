<div align="center">

# ISO/IEC 27001:2022 - Internal Audit Project

### A complete, end-to-end internal audit of an Information Security Management System (ISMS)

*Walking the full lead-auditor lifecycle, from scope definition to corrective-action follow-up, against the ISMS of a fictional SaaS company.*

<br>

![Standard](https://img.shields.io/badge/Standard-ISO%2FIEC%2027001%3A2022-0A66C2?style=for-the-badge&logo=iso&logoColor=white)
![Audit Type](https://img.shields.io/badge/Audit%20Type-Internal%20(1st%20Party)-2E7D32?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-GRC%20%7C%20InfoSec-6A1B9A?style=for-the-badge)

![Status](https://img.shields.io/badge/Status-In%20Progress-FFA000?style=flat-square)
![Scope](https://img.shields.io/badge/Scope-SaaS%20Platform-blue?style=flat-square)
![Cloud](https://img.shields.io/badge/Hosting-AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Type](https://img.shields.io/badge/Project-Educational%20%2F%20Fictional-lightgrey?style=flat-square)

</div>

---

> [!NOTE]
> **This is a fictional, educational project.** Stark Industries Inc., its staff, systems, and
> records are entirely made up to demonstrate ISO/IEC 27001:2022 internal-audit methodology. Nothing
> here represents a real organization, real audit findings, or professional audit advice.

---

## Table of Contents

- [Overview](#overview)
- [The Audited Organization](#the-audited-organization)
- [ISMS Scope](#isms-scope)
- [Key Personnel](#key-personnel)
- [Audit at a Glance](#audit-at-a-glance)
- [The 9-Stage Audit Lifecycle](#the-9-stage-audit-lifecycle)
- [Repository Structure](#repository-structure)
- [How to Use This Repository](#how-to-use-this-repository)
- [Project Status](#project-status)
- [Author](#author)

---

## Overview

This repository is a worked example of a **first-party (internal) audit** conducted under
**ISO/IEC 27001:2022**. It mirrors the real lifecycle a lead auditor follows, with every stage
producing the evidence and deliverables an auditor would generate in practice: audit plans,
clause-by-clause checklists, meeting records, findings, the final report, and corrective-action
tracking.

The audit is performed against the ISMS of a fictional SaaS company, Stark Industries Inc., whose
own policies, registers, and Statement of Applicability live in [`Supporting_Documents`](#repository-structure)
and serve as the evidence base the audit is conducted against.

---

## The Audited Organization

| Attribute | Detail |
|---|---|
| **Company** | Stark Industries Inc. |
| **Location** | New York City, New York, USA |
| **Size** | Small business |
| **Product** | A SaaS platform providing marketing-automation tools for small businesses |
| **Hosting** | Amazon Web Services (AWS) |
| **Business driver** | Prospective clients require ISO 27001 certification as a condition of procurement |

---

## ISMS Scope

> The development, deployment, and management of the **Stark Industries SaaS marketing-automation
> platform**. The scope is **strictly limited to the SaaS application** and the people, processes, and
> AWS-hosted infrastructure that support it.

---

## Key Personnel

| Role | Name |
|---|---|
| Chief Executive Officer | Tony Stark |
| Information Security Manager | Happy Hogan |
| Information Security Analyst | James Rhodes |
| Software Developer | Natalia Romanoff |
| IT Infrastructure Engineer | Maria Hill |
| Cyber Security GRC Analyst | **Nirmay Soni** |

---

## Audit at a Glance

| Item | Detail |
|---|---|
| **Standard** | ISO/IEC 27001:2022 |
| **Audit type** | Internal audit (first-party) |
| **Objective** | Assess conformity of the ISMS to ISO/IEC 27001:2022 and the organization's own requirements, and gauge readiness for certification |
| **Criteria** | ISO/IEC 27001:2022 (Clauses 4-10 and Annex A controls via the SoA), applicable legal/regulatory requirements, and internal policies |
| **Methodology** | Document review, interviews, observation, and sampling against clause-by-clause and control-by-control checklists |

---

## The 9-Stage Audit Lifecycle

| # | Stage | Purpose |
|---|---|---|
| 1 | **Define Audit Scope & Objectives** | Establish what is being audited, why, and against which criteria |
| 2 | **Develop Audit Plan** | Plan, schedule, auditee list, and methodology |
| 3 | **Prepare Audit Checklist** | Clause-by-clause checklists plus SoA and risk-treatment control checklists |
| 4 | **Conduct Opening Meeting** | Agenda, attendance, and minutes to formally start the audit |
| 5 | **Perform Audit Activities** | Interviews, document/record review, observation, sampling, evidence |
| 6 | **Identify Findings** | Classify nonconformities, observations, and opportunities for improvement |
| 7 | **Conduct Closing Meeting** | Present findings and agree on outcomes |
| 8 | **Prepare & Distribute Audit Report** | Final report, executive summary, certification-readiness assessment |
| 9 | **Follow Up on Corrective Actions** | Track corrective-action plans (CAPA) through to verified closure |

> A **`Supporting_Documents`** folder holds the auditee's existing ISMS artefacts (policies,
> registers, Statement of Applicability, asset register, and organization records) that the audit
> references throughout.

---

## Repository Structure

<details open>
<summary><b>Click to expand / collapse the full tree</b></summary>

```text
ISO27001-2022-Internal-Audit-Project
│
├── README.md
│
├── 01_Define_Audit_Scope_and_Objectives
│   ├── 01_Company_Profile
│   │   └── Company_Profile.md
│   ├── 02_Audit_Scope
│   │   └── Audit_Scope.docx
│   ├── 03_Audit_Objectives
│   │   └── Audit_Objectives.docx
│   └── 04_Audit_Criteria
│       ├── ISO27001_Criteria.docx
│       ├── Legal_Requirements.docx
│       └── Internal_Policy_References.xlsx
│
├── 02_Develop_Audit_Plan
│   ├── 01_Audit_Plan
│   │   └── Audit_Plan.docx
│   ├── 02_Audit_Schedule
│   │   └── Audit_Schedule.xlsx
│   ├── 03_Auditee_List
│   │   └── Auditee_List.xlsx
│   └── 04_Audit_Methodology
│       └── Audit_Methodology.docx
│
├── 03_Prepare_Audit_Checklist
│   ├── Clause_4_Context_of_Organization.xlsx
│   ├── Clause_5_Leadership.xlsx
│   ├── Clause_6_Planning.xlsx
│   ├── Clause_7_Support.xlsx
│   ├── Clause_8_Operation.xlsx
│   ├── Clause_9_Performance_Evaluation.xlsx
│   ├── Clause_10_Improvement.xlsx
│   ├── SoA_Control_Checklist.xlsx
│   └── Risk_Treatment_Control_Checklist.xlsx
│
├── 04_Conduct_Opening_Meeting
│   ├── Opening_Meeting_Agenda.docx
│   ├── Attendance_Record.xlsx
│   └── Opening_Meeting_Minutes.docx
│
├── 05_Perform_Audit_Activities
│   ├── 01_Interview_Records
│   │   └── Interview_Records.docx
│   ├── 02_Document_Review
│   │   ├── Policy_Review_Notes.docx
│   │   ├── Procedure_Review_Notes.docx
│   │   └── Record_Review_Notes.docx
│   ├── 03_Observation_Records
│   │   └── Observation_Notes.docx
│   ├── 04_Sampling_Records
│   │   └── Sampling_Log.xlsx
│   └── 05_Evidence_Register
│       └── Evidence_Register.xlsx
│
├── 06_Identify_Findings
│   ├── Major_Nonconformities.xlsx
│   ├── Minor_Nonconformities.xlsx
│   ├── Observations.xlsx
│   ├── Opportunities_for_Improvement.xlsx
│   └── Audit_Trail_Matrix.xlsx
│
├── 07_Conduct_Closing_Meeting
│   ├── Closing_Meeting_Agenda.docx
│   ├── Closing_Meeting_Minutes.docx
│   └── Findings_Presentation.pptx
│
├── 08_Prepare_and_Distribute_Audit_Report
│   ├── Final_Audit_Report.docx
│   ├── Executive_Summary.pdf
│   └── Certification_Readiness_Assessment.docx
│
├── 09_Follow_Up_on_Corrective_Actions
│   ├── Corrective_Action_Plan.xlsx
│   ├── CAPA_Tracker.xlsx
│   ├── Closure_Evidence.xlsx
│   └── Verification_Report.docx
│
└── Supporting_Documents
    ├── Policies
    │   ├── Information_Security_Policy.docx
    │   ├── Risk_Management_Policy.docx
    │   ├── Access_Control_Policy.docx
    │   ├── Asset_Management_Policy.docx
    │   ├── Incident_Response_Policy.docx
    │   ├── Secure_Development_Policy.docx
    │   ├── Business_Continuity_Policy.docx
    │   └── Vendor_Management_Policy.docx
    ├── Risk_Management
    │   ├── Risk_Register.xlsx
    │   └── Risk_Treatment_Plan.xlsx
    ├── Statement_of_Applicability
    │   └── SoA.xlsx
    ├── Asset_Management
    │   └── Asset_Register.xlsx
    └── Organization_Records
        ├── Org_Chart.pdf
        ├── Roles_and_Responsibilities.docx
        └── Training_Records.xlsx
```

</details>

---

## How to Use This Repository

Work through the numbered folders in order (`01` to `09`). Each stage builds on the previous one: the
scope defines the plan, the plan drives the checklists, the checklists guide the fieldwork, the
fieldwork produces the findings, and the findings flow into the report and corrective-action
follow-up. The `Supporting_Documents` folder is the auditee's evidence base referenced throughout.

| Format | Renders on GitHub? | Used for |
|---|---|---|
| `.md` | Yes (inline) | README, Company Profile |
| `.docx` `.xlsx` `.pptx` `.pdf` | No (download / preview) | Audit deliverables & evidence |

---

## Project Status

| Stage | Status |
|---|---|
| 01 - Define Audit Scope & Objectives | Complete |
| 02 - Develop Audit Plan | In progress |
| 03 - Prepare Audit Checklist | Not started |
| 04 - Conduct Opening Meeting | Not started |
| 05 - Perform Audit Activities | Not started |
| 06 - Identify Findings | Not started |
| 07 - Conduct Closing Meeting | Not started |
| 08 - Prepare & Distribute Audit Report | Not started |
| 09 - Follow Up on Corrective Actions | Not started |
| Supporting Documents | Not started |

---

## Author

**Nirmay Soni**
Cyber Security GRC Analyst, Stark Industries Inc. (fictional role for this project)
