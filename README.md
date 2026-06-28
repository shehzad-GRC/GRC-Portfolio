# 🛡️ GRC Analyst Portfolio — Shehzad Ahmad

<div align="center">

[![ISC2 CC](https://img.shields.io/badge/ISC2-Certified%20in%20Cybersecurity-0052CC?style=for-the-badge&logo=isc2&logoColor=white)](https://www.isc2.org)
[![Google](https://img.shields.io/badge/Google-Cybersecurity%20Certificate-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://coursera.org)
[![Status](https://img.shields.io/badge/Status-Open%20to%20Internships%202026-success?style=for-the-badge)](https://www.linkedin.com/in/shehzad-ahmad-3966093a5)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shehzad-ahmad-3966093a5)

</div>

---

> *"I didn't wait for experience to find me. I built the portfolio first."*
>
> This repository contains **five professional GRC deliverables** that mirror actual analyst work — built from scratch to demonstrate real capability, not just theoretical knowledge. Every artifact is based on a realistic scenario: a 50-person SaaS startup storing customer financial data, preparing for their first SOC 2 audit with no dedicated security team.

---

## 📌 About Me

I am an aspiring **GRC Analyst** specializing in Governance, Risk & Compliance. Based in Islamabad, Pakistan, I am self-taught with hands-on portfolio artifacts that go beyond certifications — because a portfolio proves more than a certificate ever will.

- 📧 **Email:** shehzad.ahmad.data@gmail.com
- 🔗 **LinkedIn:** [linkedin.com/in/shehzad-ahmad-3966093a5](https://www.linkedin.com/in/shehzad-ahmad-3966093a5)
- 🌐 **Notion Portfolio:** *(add your public Notion link here)*

---

## 🏅 Certifications

| Certification | Issuer | Status |
|---|---|---|
| ✅ Certified in Cybersecurity (CC) | ISC2 | **Earned** |
| 🔄 Google Cybersecurity Certificate | Google / Coursera | **In Progress** |
| 📅 CompTIA Security+ | CompTIA | **Planned** |
| 📅 CISA — Certified Information Systems Auditor | ISACA | **Planned (Long-term)** |

---

## 📁 Portfolio Artifacts

| # | Artifact | Framework | What It Demonstrates |
|---|---|---|---|
| [01]([./01-Risk-Register/](https://github.com/shehzad-GRC/GRC-Portfolio/blob/34f6743c27a5888f26a3e2da14ef38ffc2edf233/01%20%E2%80%94%20Risk%20Register)) | ⚠️ Risk Register | NIST CSF | Threat identification, likelihood × impact scoring, control mapping, residual risk, treatment assignment |
| [02](./02-Security-Policies/) | 📋 Security Policies | SOC 2 TSC | AUP + Password Policy authored to audit-ready standard |
| [03](./03-Vendor-Risk-Assessment/) | 🔗 Vendor Risk Assessment | ISO 27001 | 20-question third-party security questionnaire across 5 domains |
| [04](./04-NIST-CSF-Gap-Assessment/) | 📊 NIST CSF Gap Assessment | NIST CSF | 15 controls evaluated across all 5 functions with maturity scoring |
| [05](./05-Audit-Finding-Report/) | 🔍 Audit Finding Report | SOC 2 + NIST CSF | 4-part professional finding with observation, risk, evidence, and recommendation |

---

## ⚠️ 01 — Risk Register

**Scenario:** 50-person SaaS startup, customer financial data, no security team, upcoming SOC 2.

**Methodology:**
- Threat identification across NIST CSF domains (Identify · Protect · Detect · Respond · Recover)
- **Inherent Risk Score** = Likelihood (1–5) × Impact (1–5) before controls
- Control mapping with type classification: Preventive / Detective / Corrective
- **Residual Risk** re-scored after control implementation
- Risk treatment: Mitigate / Accept / Transfer / Avoid
- Risk owner assigned by job title

| Risk | Inherent Score | Severity |
|---|---|---|
| Phishing attack → account takeover | 20/25 | 🔴 Critical |
| No employee offboarding process | 16/25 | 🔴 High |
| S3 bucket misconfiguration → data exposure | 15/25 | 🔴 High |
| Ransomware attack | 15/25 | 🔴 High |
| Third-party vendor breach | 12/25 | 🟠 Medium |

📂 **Files:** `Risk-Register-SaaS-v1.0.xlsx` · `Risk-Register-Methodology.md`

---

## 📋 02 — Security Policies

**Two professional security policies authored to industry format and SOC 2 standard.**

| Document | Policy ID | Version | SOC 2 Mapping |
|---|---|---|---|
| Acceptable Use Policy | AUP-001 | v1.0 | CC6.1 |
| Password Policy | PWD-001 | v1.0 | CC6.6 |

Every policy includes: Purpose · Scope · Policy Statements · Prohibited Activities · Responsibilities · Enforcement · Review Cycle · Version History

📂 **Files:** `AUP-001-Acceptable-Use-Policy-v1.0.pdf` · `PWD-001-Password-Policy-v1.0.pdf`

---

## 🔗 03 — Vendor Risk Assessment

**20-question security questionnaire for third-party vendor evaluation before granting system or data access.**

| Domain | Questions |
|---|---|
| 🔐 Security Controls | 6 — MFA, encryption, pen testing, patch management, breach history |
| 🗄️ Data Handling | 4 — Storage countries, retention, access controls, deletion |
| ✅ Compliance Certifications | 4 — SOC 2, ISO 27001, HIPAA, security training |
| 🔄 Business Continuity | 3 — BCP, SLA, DR testing |
| ⚖️ Legal & Governance | 3 — Cyber insurance, DPA, subcontractor security |

**Output:** Vendor risk summary rated **Low / Medium / High** with findings narrative.

📂 **Files:** `Vendor-Risk-Questionnaire-v1.0.xlsx` · `Sample-Vendor-Assessment-Completed.pdf`

---

## 📊 04 — NIST CSF Gap Assessment

**Gap assessment across all 5 NIST CSF functions using a 1–5 maturity scale.**

| NIST Function | Avg Maturity | Status |
|---|---|---|
| 🔍 Identify | 2.0 / 5 | ⚠️ Weak |
| 🛡️ Protect | 2.5 / 5 | 🔶 Developing |
| 🚨 Detect | 1.7 / 5 | 🔴 Critical Gap |
| 📢 Respond | 2.0 / 5 | ⚠️ Weak |
| 🔁 Recover | 1.5 / 5 | 🔴 Critical Gap |

**Maturity Scale:** 1 = Does not exist · 2 = Ad hoc · 3 = Documented · 4 = Monitored · 5 = Optimized

**Priority gaps:** Detect (no SIEM, minimal logging) · Recover (no tested DR plan)

📂 **Files:** `NIST-CSF-Gap-Assessment-v1.0.xlsx` · `Gap-Assessment-Remediation-Roadmap.md`

---

## 🔍 05 — Audit Finding Report

**Professional audit finding using the 4-part structure: Observation · Risk · Evidence · Recommendation**

| Field | Detail |
|---|---|
| Finding ID | FIND-2026-001 |
| Title | Inadequate Access Revocation Upon Employee Termination |
| Severity | 🔴 **High** |
| SOC 2 Mapping | CC6.2 — Logical and Physical Access Controls |
| NIST CSF Mapping | PR.AC-1 — Identities and Credentials Managed |
| Observation | 4 of 10 terminated employees retained active access 10+ business days post-termination |
| Root Cause | Manual offboarding; no HRIS-to-AD automated deprovisioning |
| Recommendation | Automated HRIS-to-AD deprovisioning · 24-hour SLA · Monthly reconciliation |
| Remediation Due | 30 days from finding issuance |

📂 **Files:** `Audit-Finding-FIND-2026-001.pdf` · `Finding-Remediation-Tracker.xlsx`

---

## 🛠️ Core Skills

**Frameworks**
`NIST CSF` `SOC 2 Type I & II` `ISO/IEC 27001` `HIPAA` `PCI DSS`

**GRC Platforms**
`Vanta` `Drata` `ServiceNow GRC` `OneTrust` `Archer` `Microsoft Excel`

**Competencies**
`Risk Assessment` `Gap Analysis` `Control Testing` `Evidence Collection` `Policy Writing` `Vendor Risk Management` `Audit Finding Documentation` `Risk Register Maintenance`

---

## 📬 Contact

<div align="center">

| 🔗 LinkedIn | 📧 Email |
|---|---|
| [linkedin.com/in/shehzad-ahmad-3966093a5](https://www.linkedin.com/in/shehzad-ahmad-3966093a5) | shehzad.ahmad.data@gmail.com |

</div>

---

<div align="center">

*Portfolio built: June 2026 · All scenarios are fictional and created for educational and demonstration purposes.*

</div>
