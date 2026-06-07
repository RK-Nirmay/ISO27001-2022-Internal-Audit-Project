<div align="center">

# ISO/IEC 27001:2022 Internal Audit Project

### A complete, end-to-end internal audit of an Information Security Management System (ISMS)

![Standard](https://img.shields.io/badge/Standard-ISO%2FIEC%2027001%3A2022-1f6fc2)
![Type](https://img.shields.io/badge/Type-Internal%20Audit-2e7d32)
![Scope](https://img.shields.io/badge/Scope-SaaS%20Platform%20(AWS)-555555)
![Stages](https://img.shields.io/badge/Stages-9%2F9%20Complete-2e7d32)
![Status](https://img.shields.io/badge/Status-Complete-2e7d32)

</div>

---

## Overview

This repository documents a full ISO/IEC 27001:2022 internal audit, carried out across the nine
stages of the audit lifecycle, from defining the scope through to verifying corrective actions, with
a supporting library of the ISMS documents that were audited.

It is a learning and portfolio project built around a fictional company, **Stark Industries Inc.**, a
small US-based SaaS company in New York City that operates a cloud-hosted marketing-automation
platform on Amazon Web Services. The ISMS scope is the SaaS platform and its supporting people,
processes, and infrastructure. The audit was conducted from 16 to 20 March 2026, with the report
issued on 30 March 2026.

> Stark Industries Inc. and all named individuals are fictional, created for this educational
> exercise. The audit, its evidence, and its findings are illustrative.

---

## Audit outcome at a glance

| Result | Count |
|---|---|
| Major nonconformities | 0 |
| Minor nonconformities | 3 (all closed) |
| Opportunities for improvement | 2 |
| Overall conclusion | Largely conforming; broadly ready for certification once minor findings are closed |

---

## Completion status

| Stage | Folder | Status |
|---|---|---|
| 01 | Define Audit Scope and Objectives | Complete |
| 02 | Develop Audit Plan | Complete |
| 03 | Prepare Audit Checklist | Complete |
| 04 | Conduct Opening Meeting | Complete |
| 05 | Perform Audit Activities | Complete |
| 06 | Identify Findings | Complete |
| 07 | Conduct Closing Meeting | Complete |
| 08 | Prepare Audit Report | Complete |
| 09 | Corrective Action Follow-Up | Complete |
| - | Supporting Documents | Complete |

---

## Repository structure

```
ISO27001-2022-Internal-Audit-Project/
├── README.md
│
├── 01_Define_Audit_Scope_and_Objectives/
│   ├── 01_Company_Profile/        Company_Profile.md
│   ├── 02_Audit_Scope/            Audit_Scope.docx
│   ├── 03_Audit_Objectives/       Audit_Objectives.docx
│   ├── 04_Audit_Criteria/         ISO27001_Criteria.docx, Internal_Policy_References.xlsx, Legal_Requirements.docx
│   └── README.md
│
├── 02_Develop_Audit_Plan/
│   ├── 01_Audit_Plan/             Audit_Plan.docx
│   ├── 02_Audit_Schedule/         Audit_Schedule.xlsx
│   ├── 03_Auditee_List/           Auditee_List.xlsx
│   ├── 04_Audit_Methodology/      Audit_Methodology.docx
│   └── README.md
│
├── 03_Prepare_Audit_Checklist/
│   ├── ISO27001_Clause_Audit_Checklist.xlsx
│   ├── Stark_Industries_Assets_Risk_Assessment_SoA.xlsx
│   ├── Stark_Industries_Control_Evidence_Tracker.xlsx
│   └── README.md
│
├── 04_Conduct_Opening_Meeting/
│   ├── Stark_ISMS_Management_Meeting_Agenda_Minutes.xlsx
│   └── README.md
│
├── 05_Perform_Audit_Activities/
│   ├── Audit_Fieldwork_Log.xlsx
│   └── README.md
│
├── 06_Identify_Findings/
│   ├── Stark_ISMS_NonConformity_Log.xlsx
│   └── README.md
│
├── 07_Conduct_Closing_Meeting/
│   ├── Stark_ISMS_Closing_Meeting_Agenda_Minutes.xlsx
│   └── README.md
│
├── 08_Prepare_Audit_Report/
│   ├── Final_Audit_Report.docx
│   └── README.md
│
├── 09_Corrective_Action_Followup/
│   ├── Corrective_Action_Plan.xlsx
│   └── README.md
│
└── Supporting_Documents/
    ├── ISMS_Clause_Documents/         The ISMS policies and procedures (Clauses 4 to 9)
    ├── Policies/                      Topic-specific security policies
    ├── Statement_of_Applicability/    Combined Asset Register, Risk Assessment, SoA, Legend workbook
    ├── Risk_Management/               Reference to the combined workbook
    ├── Asset_Management/              Reference to the combined workbook
    ├── Incident_Management/           Chain of Custody Form (control A.5.28)
    ├── Control_Evidence_Tracker.xlsx
    └── README.md
```

---

## The nine stages

| Stage | Purpose |
|---|---|
| 01 Define Audit Scope and Objectives | Sets what the audit covers and why, with the company profile, scope, objectives, and criteria |
| 02 Develop Audit Plan | Plans the audit: plan, schedule, auditee list, and methodology |
| 03 Prepare Audit Checklist | Working papers: the clause checklist, plus the SoA and control evidence records |
| 04 Conduct Opening Meeting | Kicks off the audit with the auditees (agenda, minutes, attendance) |
| 05 Perform Audit Activities | Fieldwork: evidence register, interview and observation notes, sampling record |
| 06 Identify Findings | Formalises the nonconformities and opportunities for improvement |
| 07 Conduct Closing Meeting | Presents the findings, conclusion, and next steps |
| 08 Prepare Audit Report | The full audit report for management and stakeholders |
| 09 Corrective Action Follow-Up | Corrective actions, auditor verification, and closure |

---

## Findings summary

| Ref | Finding | Type | Clause / Control | Status |
|---|---|---|---|---|
| NC-1 | Legal and regulatory requirements not formally identified | Minor NC | 4.2 / A.5.31 | Closed |
| NC-2 | Segregation of duties not formally addressed | Minor NC | A.5.3 | Closed |
| NC-3 | Periodic access reviews not evidenced | Minor NC | A.5.18 / A.8.2 | Closed |
| OFI-1 | Single-cloud (AWS) dependency, no documented exit plan | OFI | A.5.30 | In Progress |
| OFI-2 | Training-completion tracking is informal | OFI | A.6.3 | Implemented |

All three nonconformities were corrected, verified as effective, and closed, completing the audit
cycle.

---

## Supporting documents

The `Supporting_Documents` folder holds the auditee's ISMS records, the documents the audit
examined: the ISMS clause documents (scope, policy, roles, risk processes, objectives, competence,
monitoring, management review, internal audit programme), the topic-specific policies, the combined
Asset Register / Risk Assessment / Statement of Applicability workbook, the Control Evidence Tracker,
and the incident-response Chain of Custody form.

---

## About this project

This project demonstrates the complete internal audit process for ISO/IEC 27001:2022, including the
working papers, meeting records, findings, report, corrective-action follow-up, and the underlying
ISMS document library that a real audit relies on.

**Author:** Nirmay Soni, Cyber Security GRC Analyst
