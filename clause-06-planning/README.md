## 📁 clause-06-planning

ISO 27001:2022 — Clause 6: Planning

This folder contains the complete risk management documentation
for Aman FinTech's ISMS — from methodology through to treatment,
all contained in a single master Excel workbook with 9 sheets.

### Master File: 6.1a_Risk_Assessment_Complete.xlsx

| Sheet | Document ID | Contents | Records |
|---|---|---|---|
| Sheet 1 — Methodology | ISMS-RAM-001 | Risk scoring formula (L × I), 1–5 scale, risk appetite definition, likelihood and impact criteria, treatment options | — |
| Sheet 2 — Asset Register | ISMS-AST-001 | 62 assets across 6 groups: Customer Data (17) · Core Systems (20) · Infrastructure (9) · Third-Party APIs (9) · People & Process (5) · Physical (4) | 62 |
| Sheet 3 — Threat Register | ISMS-THR-001 | 130 threats mapped using STRIDE methodology. External: 94 (72%) · Internal: 36 (28%). STRIDE breakdown: S:20 T:26 R:7 I:31 D:30 E:16 | 130 |
| Sheet 4 — Vulnerability Register | ISMS-VUL-001 | 45 vulnerabilities identified using ISO 27005 + CWE + NIST SP 800-30. 10 root cause categories. Each vulnerability mapped to CIA impact and linked to internal issues from Clause 4.1 | 45 |
| Sheet 5 — Risk Assessment | ISMS-RAR-001 | 130 risks scored (Asset × Threat × Vulnerability). Critical: 36 · High: 58 · Medium: 35 · Low: 1 | 130 |
| Sheet 6 — Risk Treatment Plan | ISMS-RTP-001 | 125 treatment entries with ISO 27001:2022 Annex A control mapping. P1(30d): 62 · P2(90d): 38 · P3(180d): 22 · Transfer: 3. Residual risk: Critical: 0 · High: 3 · Medium: 80 · Low: 42 | 125 |
| Sheet 7 — Statement of Applicability | ISMS-SOA-001 | All 93 Annex A controls evaluated. Included: 92 · Excluded: 1 (8.34 — justified). Theme 5: 37 · Theme 6: 8 · Theme 7: 14 · Theme 8: 33 | 93 |
| Sheet 8 — Security Objectives | ISMS-OBJ-001 | 19 KPI-based objectives across 4 levels: Strategic (3) · Operational (6) · Compliance (4) · Technical (6). Each with target, baseline, owner, and Year-1 milestone | 19 |
| Sheet 9 — Change Management | ISMS-CHG-001 | Change management procedure (8 types, approval matrix, 8-step process) + Year-1 change register with 18 planned ISMS changes across Q2 2026 – Q1 2027 | 18 |

### Risk Profile Summary

| Stage | ⛔ Critical | 🔴 High | 🟡 Medium | 🟢 Low |
|---|---|---|---|---|
| **Before Treatment** | 36 | 58 | 35 | 1 |
| **After Treatment** | 0 | 3 | 80 | 42 |

### Annex A Controls Distribution

| Theme | Controls | Focus |
|---|---|---|
| Theme 5 — Organizational | 37 included | Identity, access, suppliers, governance, incident, BCP |
| Theme 6 — People | 8 included | Screening, awareness, training, HR lifecycle |
| Theme 7 — Physical | 14 included | Physical access, equipment, environmental |
| Theme 8 — Technological | 33 included | Network, cryptography, application security, monitoring |
