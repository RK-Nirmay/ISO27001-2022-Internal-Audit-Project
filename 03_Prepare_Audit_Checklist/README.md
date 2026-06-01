# Stage 03 - Prepare Audit Checklist

This stage turns the audit criteria (Stage 01) and the audit plan (Stage 02) into the working
papers the auditor uses during fieldwork. A checklist captures, for each requirement and control:
what the standard asks, the question the auditor puts to the auditee, the evidence examined, and
the result.

The results recorded here reflect the conducted audit and are consistent across every later stage
(findings, report, and corrective actions).

## Contents (this folder)

| File | Purpose |
|---|---|
| `ISO27001_Clause_Audit_Checklist.xlsx` | Management-clause checklist with one tab per clause (Clause 4 to Clause 10). Covers all 30 mandatory requirements with audit question, evidence, auditee, result, and notes. |

## Related records (maintained in Supporting_Documents)

The Annex A control assessment and the risk-treatment verification are recorded directly in the
organisation's own records rather than duplicated into separate checklist files. These are the
auditee records the auditor assessed during this stage:

| Record | Location | What it provides |
|---|---|---|
| `Stark_Industries_Assets_Risk_Assessment_SoA.xlsx` | `Supporting_Documents/Statement_of_Applicability` | One combined workbook with four tabs: Asset Register, Risk Assessment, SOA, and Legend. The SOA tab gives applicability and justification for all 93 Annex A controls; the Risk Assessment tab gives the risk treatment (controls, residual risk, owner, status). |
| `Stark_Industries_Control_Evidence_Tracker.xlsx` | `Supporting_Documents` | Implementation status and evidence reference for each control. |

This keeps a single source of truth: the auditor assesses the organisation's actual SoA, risk, and
evidence records instead of duplicating them.

## Audit result summary

- Clause checklist: conforming across Clauses 4 to 10, with one Minor nonconformity at Clause 4.2
  (legal and regulatory requirements not formally identified).
- Annex A controls: 83 applicable and 10 not applicable (physical/data-centre controls delivered by
  AWS under the shared-responsibility model). The large majority conforming, with findings on
  segregation of duties, access-rights review, single-cloud dependency, and training-completion
  tracking.

Findings are formalised in Stage 06 (Identify Findings).

> Note: `.xlsx` files do not preview inline on GitHub. Download them to view the full workbook.
