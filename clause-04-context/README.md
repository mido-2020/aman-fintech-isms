## 📁 clause-04-context

ISO 27001:2022 — Clause 4: Context of the Organization

This folder contains the foundational context analysis documents
that define the environment in which Aman FinTech's ISMS operates.

| Document | ID | Description |
|---|---|---|
| 4.1a_External_Issues_Register.xlsx | ISMS-EXT-001 | 62 external issues identified using PESTLE + Porter's 5 Forces framework. Covers Political, Economic, Social, Technological, Legal, Environmental factors + competitive forces specific to the Egyptian and Saudi FinTech market. |
| 4.1b_Internal_Issues_Register.xlsx | ISMS-INT-001 | 38 internal issues identified using McKinsey 7S + SWOT analysis. Covers organizational strengths, weaknesses, structural gaps, and cultural factors across Cairo HQ and Riyadh office. |
| 4.2_Interested_Parties_Register.xlsx | ISMS-IP-001 | 60 interested parties mapped using a Power/Interest Grid. Includes regulators (CBE, SAMA), customers, vendors, investors, employees, and third-party API providers — each with security requirements and engagement strategy. |
| 4.4_ISMS_Declaration.docx | ISMS-DCL-001 | Formal bilingual (EN/AR) ISMS Declaration signed by the Board of Directors. States the organization's commitment to establish, implement, maintain, and continually improve the ISMS per ISO 27001:2022 Clause 4.4. |

> **Note:** The ISMS Scope document (ISMS-SCP-001) is summarized below.

### ISMS Scope Summary — ISMS-SCP-001

**Scope Statement:**
The ISMS covers the design, development, operation, and support of
Aman FinTech's e-wallet, money transfer, digital lending, and
e-payment services, including all associated information assets,
personnel, processes, and technology infrastructure across the
Cairo HQ and Riyadh office.

| Dimension | In Scope |
|---|---|
| **Organizational** | All 10 departments + 50 employees + contractors |
| **Geographical** | Cairo HQ (On-Premise DC) + Riyadh Office + DEEM Saudi Cloud + AWS (non-critical) |
| **Technological** | Mobile App + Core Banking + Payment Gateway + AML System + APIs + Security Stack |
| **Services** | E-Wallet + Money Transfer + Digital Lending + E-Payment |
| **Regulatory** | CBE (Egypt) + SAMA (Saudi Arabia) + PCI DSS + Egyptian Data Protection Law 2020 |

**Key Exclusions:** Personal devices not enrolled in MDM | Non-critical AWS workloads (dev/test only)
