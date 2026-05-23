# 🔐 Aman FinTech — ISMS Documentation Portfolio

![ISO 27001](https://img.shields.io/badge/ISO%2027001-2022-blue?style=flat-square&logo=shield)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat-square)
![Clauses](https://img.shields.io/badge/Clauses%20Complete-6%20of%2010-green?style=flat-square)
![Risks](https://img.shields.io/badge/Risks%20Assessed-130-red?style=flat-square)
![Controls](https://img.shields.io/badge/Annex%20A%20Controls-93-purple?style=flat-square)

---

## 📋 Project Overview

A **complete, audit-ready ISMS documentation portfolio** built from scratch for **أمان فينتك (Aman FinTech)** — a fictional Egyptian-Saudi FinTech company used as a real-world simulation for ISO/IEC 27001:2022 implementation.

This project demonstrates end-to-end ISMS implementation capability across all ISO 27001:2022 clauses, producing professional-grade documentation aligned with **CBE (Egypt)**, **SAMA (Saudi Arabia)**, **PCI DSS**, and **Egyptian Data Protection Law 2020** requirements.

---

## 🏢 Company Profile

| Attribute | Details |
|---|---|
| **Company** | أمان فينتك — Aman FinTech |
| **Services** | E-Wallet · Money Transfer · Digital Lending · E-Payment |
| **Employees** | 50 staff across Cairo HQ and Riyadh office |
| **Customers** | 200,000 active customers |
| **Architecture** | Hybrid — On-Premise Cairo + DEEM Saudi Cloud + AWS |
| **Regulators** | CBE (Egypt) · SAMA (Saudi Arabia) |
| **Standards** | ISO 27001:2022 · PCI DSS · Egyptian DPL 2020 · FATF/AML |

---

## 📊 ISMS Progress Tracker

| Clause | Title | Status | Key Deliverable | Records |
|---|---|---|---|---|
| **4.1** | External Issues | ✅ Complete | ISMS-EXT-001 | 62 issues |
| **4.1** | Internal Issues | ✅ Complete | ISMS-INT-001 | 38 issues |
| **4.2** | Interested Parties | ✅ Complete | ISMS-IP-001 | 60 parties |
| **4.3** | ISMS Scope | ✅ Complete | ISMS-SCP-001 | 44 items |
| **4.4** | ISMS Declaration | ✅ Complete | ISMS-DCL-001 | — |
| **5.1** | Leadership | ✅ Complete | ISMS-LDR-001 | 9 requirements |
| **5.2** | Security Policy | ✅ Complete | ISMS-ISP-001 | — |
| **5.3** | Roles & RACI | ✅ Complete | ISMS-RACI-001 | 12 roles |
| **6.1** | Risk Methodology | ✅ Complete | ISMS-RAM-001 | — |
| **6.1** | Asset Register | ✅ Complete | ISMS-AST-001 | 62 assets |
| **6.1** | Threat Register | ✅ Complete | ISMS-THR-001 | 130 threats |
| **6.1** | Vulnerability Register | ✅ Complete | ISMS-VUL-001 | 45 vulnerabilities |
| **6.1** | Risk Assessment | ✅ Complete | ISMS-RAR-001 | 130 risks |
| **6.1** | Risk Treatment Plan | ✅ Complete | ISMS-RTP-001 | 125 treatments |
| **6.1** | Statement of Applicability | ✅ Complete | ISMS-SOA-001 | 93 controls |
| **6.2** | Security Objectives | ✅ Complete | ISMS-OBJ-001 | 19 objectives |
| **6.3** | Planning of Changes | ✅ Complete | ISMS-CHG-001 | 18 changes |
| **7.1–7.5** | Support | 🔄 In Progress | ISMS-RES/CMP/AWR/COM/DOC | — |
| **8.1–8.3** | Operation | ⏳ Pending | ISMS-OPS-001 | — |
| **9.1–9.3** | Performance Evaluation | ⏳ Pending | ISMS-MON/AUD/MRV | — |
| **10.1–10.2** | Improvement | ⏳ Pending | ISMS-IMP/NCA | — |

---

## 📈 Key Statistics

| Category | Count | Details |
|---|---|---|
| **Assets Identified** | 62 | 6 groups: Data · Systems · Infrastructure · APIs · People · Physical |
| **Threats Mapped** | 130 | STRIDE methodology · 72% External · 28% Internal |
| **Vulnerabilities Identified** | 45 | ISO 27005 + CWE + NIST SP 800-30 |
| **Risks Assessed** | 130 | Critical: 36 · High: 58 · Medium: 35 · Low: 1 |
| **Risks After Treatment** | — | Critical: 0 · High: 3 · Medium: 80 · Low: 42 |
| **Annex A Controls** | 93 | Included: 92 · Excluded: 1 (justified) |
| **Security Objectives** | 19 | Strategic · Operational · Compliance · Technical |
| **Treatment Actions** | 125 | P1(30d): 62 · P2(90d): 38 · P3(180d): 22 · Transfer: 3 |

---

## 🗂️ Document Index

### Clause 4 — Context of the Organization
```
clause-04-context/
├── 4.1a_External_Issues_Register.xlsx      ISMS-EXT-001  62 issues  PESTLE + Porter's 5 Forces
├── 4.1b_Internal_Issues_Register.xlsx      ISMS-INT-001  38 issues  McKinsey 7S + SWOT
├── 4.2_Interested_Parties_Register.xlsx    ISMS-IP-001   60 records Power/Interest Grid
├── 4.3_ISMS_Scope.xlsx                     ISMS-SCP-001  44 items   Org/Geo/Tech/Services
└── 4.4_ISMS_Declaration.docx               ISMS-DCL-001  —          Bilingual EN/AR
```

### Clause 5 — Leadership
```
clause-05-leadership/
├── 5.1_5.3_Leadership_RACI.xlsx            ISMS-LDR-001 + ISMS-RACI-001
└── 5.2_Information_Security_Policy.docx    ISMS-ISP-001  Bilingual EN/AR
```

### Clause 6 — Planning (Master File — 9 Sheets)
```
clause-06-planning/
└── 6.1a_Risk_Assessment_Complete.xlsx
    ├── Sheet 1  Methodology         ISMS-RAM-001  Risk scoring + appetite
    ├── Sheet 2  Asset Register       ISMS-AST-001  62 assets across 6 groups
    ├── Sheet 3  Threat Register      ISMS-THR-001  130 threats (STRIDE)
    ├── Sheet 4  Vulnerability Reg.   ISMS-VUL-001  45 vulnerabilities
    ├── Sheet 5  Risk Assessment      ISMS-RAR-001  130 risks scored
    ├── Sheet 6  Risk Treatment Plan  ISMS-RTP-001  125 Annex A treatments
    ├── Sheet 7  Statement of Appl.   ISMS-SOA-001  93 controls evaluated
    ├── Sheet 8  Security Objectives  ISMS-OBJ-001  19 KPI-based objectives
    └── Sheet 9  Change Management    ISMS-CHG-001  18 Year-1 changes
```

---

## 🔧 Methodology Summary

| Phase | Framework Used |
|---|---|
| External Context | PESTLE + Porter's 5 Forces |
| Internal Context | McKinsey 7S + SWOT |
| Stakeholder Analysis | Power / Interest Grid |
| Asset Identification | Process-Based + ISO 27005 Categories |
| Threat Identification | STRIDE + Asset-Driven + Source-Based |
| Vulnerability Identification | ISO 27005 + CWE + NIST SP 800-30 |
| Risk Scoring | Likelihood × Impact (1–5 scale) |
| Risk Treatment | ISO 27001:2022 Annex A (93 controls, 4 themes) |
| Objectives | 4-Level KPI Framework (Strategic/Operational/Compliance/Technical) |

---

## 🤖 AI Agent

> **Note:** The ISMS AI Agent source code is maintained in a **private repository** to protect implementation details.
>
> The agent automates the entire ISMS building process — accepting structured company inputs and generating audit-ready documentation matching the standards established in this project.

**Agent capabilities (in development):**
- Automated risk assessment from company profile inputs
- Threat and vulnerability generation per asset group
- Annex A control mapping from root cause categories
- Excel register generation with full formatting
- Cross-reference validation across all ISMS documents

---

## 👤 About

**Moamen Mohamed** — Senior Cybersecurity & GRC Consultant

[![CISSP](https://img.shields.io/badge/CISSP-Certified-blue?style=flat-square)](https://www.isc2.org)
[![ISO 27001 LI](https://img.shields.io/badge/ISO%2027001-Lead%20Implementer-blue?style=flat-square)](https://www.iso.org)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://linkedin.com/in/GitHub_user)

> Security Architecture · Risk Management · GRC · Penetration Testing · ISO 27001 Implementation

---

## 📄 License

This project is for **educational and portfolio purposes**.
All company names, customer data, and financial figures are entirely fictional.

---

*Last updated: April 2026 | Clauses 4–6 complete | Targeting ISO 27001:2022 certification simulation*
