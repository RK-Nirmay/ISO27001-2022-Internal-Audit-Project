# Company Profile - Stark Industries Inc.

> **Document:** Company Profile
> **Stage:** 01 - Define Audit Scope & Objectives
> **Project:** ISO/IEC 27001:2022 Internal Audit
> **Status:** Baseline reference document
> **Prepared by:** Nirmay Soni, Cyber Security GRC Analyst

> [!NOTE]
> Fictional, educational profile created for an ISO/IEC 27001:2022 internal-audit exercise.
> Stark Industries Inc. and all named individuals are illustrative and do not represent any real entity.

---

## 1. Company Snapshot

| Attribute | Detail |
|---|---|
| **Legal name** | Stark Industries Inc. |
| **Headquarters** | New York City, New York, USA |
| **Industry** | Software (Software as a Service, SaaS) |
| **Company size** | Small business (about 6 core staff) |
| **Flagship product** | A SaaS marketing-automation platform for small businesses |
| **Hosting model** | Fully cloud-hosted on Amazon Web Services (AWS) |
| **Operating market** | United States, serving small-business clients |
| **Certification goal** | ISO/IEC 27001:2022 certification (scope limited to the SaaS platform) |

---

## 2. Business Overview

Stark Industries Inc. is a small, US-based software company that develops and operates a
**cloud-based marketing-automation platform** designed for small businesses. The platform helps
clients manage marketing campaigns, automate customer outreach, and track engagement, and in doing
so it processes and stores customer and end-user data on behalf of those clients.

The entire product is delivered as a **Software-as-a-Service (SaaS)** offering hosted on **Amazon Web
Services**, meaning the company's value, reputation, and customer trust are tightly bound to the
**confidentiality, integrity, and availability** of the platform and the data it handles.

---

## 3. Strategic Driver for the ISMS

The decision to build an ISMS and pursue ISO 27001 certification is **commercially driven**:

> **Prospective clients increasingly require ISO 27001 certification as a precondition for
> procurement.** Without it, Stark Industries is excluded from sales opportunities, particularly
> with larger or more security-conscious customers.

Certification is therefore positioned as a **growth enabler** (unlocking new sales and improving
customer trust) as much as a security and compliance objective.

---

## 4. Product & Service Description

| Aspect | Detail |
|---|---|
| **Product type** | Multi-tenant SaaS marketing-automation application |
| **Target users** | Small businesses and their marketing teams |
| **Core functions** | Campaign management, marketing automation, customer-engagement tracking |
| **Data handled** | Client account data, end-customer contact/marketing data, usage & engagement data |
| **Delivery** | Web-based application accessed over the internet |
| **Infrastructure** | Amazon Web Services (compute, storage, database, networking) |

---

## 5. Organizational Structure & Roles

| Role | Name | Primary Responsibility |
|---|---|---|
| Chief Executive Officer | Tony Stark | Overall leadership, strategy, top-management commitment to the ISMS |
| Information Security Manager | Happy Hogan | Owns the ISMS; drives implementation and certification |
| Information Security Analyst | James Rhodes | Day-to-day security monitoring, controls, and analysis |
| Software Developer | Natalia Romanoff | Develops and maintains the SaaS application (secure development) |
| IT Infrastructure Engineer | Maria Hill | Manages AWS infrastructure, configuration, and operations |
| Cyber Security GRC Analyst | **Nirmay Soni** | Builds ISMS governance, risk, and compliance; supports the audit |

> With a small team, individuals carry **multiple responsibilities**, which makes clear role
> definition, segregation of duties, and documented procedures especially important for the ISMS.

---

## 6. Technology Environment

| Layer | Detail |
|---|---|
| **Cloud provider** | Amazon Web Services (AWS) |
| **Application** | Proprietary SaaS marketing-automation platform |
| **Architecture** | Cloud-native, multi-tenant, internet-facing web application |
| **Key dependencies** | AWS as the primary infrastructure and a critical third-party supplier |
| **Access model** | Remote access by a small distributed team |

> Because AWS underpins the entire platform, the **shared-responsibility model** and **vendor
> management** of AWS are central considerations for the ISMS.

---

## 7. Context of the Organization (ISO 27001 Clause 4.1)

### External Issues
- Growing customer and market expectation for demonstrable security (ISO 27001 as a buying criterion).
- US data-protection and privacy obligations applicable to customer/end-user data.
- Evolving cyber-threat landscape targeting SaaS and cloud-hosted platforms.
- Heavy reliance on a single major cloud provider (AWS) and its service availability.

### Internal Issues
- Small team with overlapping roles and limited dedicated security resourcing.
- Maturing (early-stage) security documentation, policies, and processes.
- Rapid product development cycles that must integrate security (secure by design).
- Need to formalize governance, risk management, and evidence for certification.

---

## 8. Interested Parties (ISO 27001 Clause 4.2)

| Interested Party | Key Needs & Expectations |
|---|---|
| **Customers (small businesses)** | Protection of their and their end-customers' data; ISO 27001 assurance |
| **End customers (clients' customers)** | Privacy and security of personal/marketing data |
| **Top management / CEO** | Certification achieved; reputation and sales growth protected |
| **Employees** | Clear security responsibilities, training, and usable processes |
| **AWS (cloud provider)** | Compliance with AWS terms; correct use of shared-responsibility controls |
| **Regulators** | Compliance with applicable US data-protection and privacy law |
| **Prospective clients / procurement** | Valid ISO 27001 certification before contracting |

---

## 9. ISMS Scope Statement (Preview)

> The Information Security Management System covers the **development, deployment, and management of
> the Stark Industries SaaS marketing-automation platform**, including the people, processes, and
> AWS-hosted infrastructure that support it. The scope is **strictly limited to the SaaS application**.

*(The formal scope is detailed in `02_Audit_Scope/Audit_Scope.docx`.)*

---

## 10. Document Control

| Field | Detail |
|---|---|
| **Document title** | Company Profile - Stark Industries Inc. |
| **Version** | 1.0 |
| **Author** | Nirmay Soni (Cyber Security GRC Analyst) |
| **Reviewed by** | Happy Hogan (Information Security Manager) |
| **Classification** | Internal |
| **Next document** | `02_Audit_Scope/Audit_Scope.docx` |
