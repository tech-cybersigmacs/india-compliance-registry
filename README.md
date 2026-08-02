# India Compliance Registry

**40 verified compliance facts across 24 frameworks** — every entry cites its primary source (Gazette, regulator, standards body) and carries a last-verified date. Maintained by [CyberSigma](https://cybersigmacs.com), a CERT-In empanelled, PCI SSC-listed QSA firm.

Registry version: **v1.7.0** · Canonical live version: <https://cybersigmacs.com/compliance-registry/> · Machine-readable: [registry.json](registry.json)

## Why this exists

Compliance dates get misquoted constantly. This registry is verify-first: nothing enters without a primary source, corrections are appended (never silent), and where authoritative sources disagree, the disagreement is stated. Licensed CC BY 4.0 — cite freely with attribution.

## Open artifacts in this repo

- [CERT-In Directions readiness checklist](cert-in-directions-checklist.md) — 6-hour reporting, 180-day logs, every obligation sourced
- [DPDP compliance timeline](dpdp-compliance-timeline.md) — every date sourced to the Gazette, through the May 2027 phase-in
- [India incident-reporting map](india-incident-reporting-map.md) — one incident, every regulator clock, side by side
- [PCI DSS SAQ eligibility table](pci-saq-eligibility-table.md) — all nine SAQ types and the catch in each

## The facts, by framework

### CERT-In Directions

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Issue and commencement | Directions under Section 70B(6), IT Act 2000 issued 28 April 2022; effective 28 June 2022. Apply to service providers, intermediaries, data centres, body corporates and government organisations. | 2022-06-28 | [CERT-In Directions (official PDF)](https://www.cert-in.org.in/PDF/CERT-In_Directions_70B_28.04.2022.pdf) | 2026-07-31 |
| Incident reporting window | Specified cyber incidents must be reported to CERT-In within 6 hours of noticing. | 2022-06-28 | [CERT-In Directions (official PDF)](https://www.cert-in.org.in/PDF/CERT-In_Directions_70B_28.04.2022.pdf) | 2026-07-31 |
| Log retention | ICT system logs must be maintained for a rolling 180 days, within Indian jurisdiction. | 2022-06-28 | [CERT-In Directions (official PDF)](https://www.cert-in.org.in/PDF/CERT-In_Directions_70B_28.04.2022.pdf) | 2026-07-31 |
| Time synchronisation | System clocks must be synchronised to NIC or NPL time sources. | 2022-06-28 | [CERT-In Directions (official PDF)](https://www.cert-in.org.in/PDF/CERT-In_Directions_70B_28.04.2022.pdf) | 2026-07-31 |
| Provider record-keeping | Data centres, VPS, cloud and VPN providers must register and retain accurate subscriber/customer records for 5 years after cancellation or withdrawal of service. | 2022-06-28 | [CERT-In Directions (official PDF)](https://www.cert-in.org.in/PDF/CERT-In_Directions_70B_28.04.2022.pdf) | 2026-07-31 |

### CMMC (US DoD)

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Programme and acquisition rule dates | The CMMC Program rule (32 CFR Part 170) was published 15 October 2024 and took effect 16 December 2024. The acquisition rule (48 CFR) took effect 10 November 2025, starting a phased rollout that adds CMMC requirements to DoD contracts in four annual phases. | 2025-11-10 | [US Federal Register — CMMC Program rule (32 CFR 170)](https://www.federalregister.gov/documents/2024/10/15/2024-22905/cybersecurity-maturity-model-certification-cmmc-program) | 2026-08-01 |

### DPDP Act 2023

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Enactment | Digital Personal Data Protection Act, 2023 (Act No. 22 of 2023); Presidential assent 11 August 2023; Gazette ID CG-DL-E-12082023-248045. | 2023-08-11 | [Official Gazette text (MeitY PDF)](https://www.meity.gov.in/static/uploads/2024/06/2bf1f0e9f04e6fb4f8fef35e82c42aa5.pdf) | 2026-07-31 |
| DPDP Rules 2025 notification | Digital Personal Data Protection Rules, 2025 notified 13 November 2025 as G.S.R. 843(E), Gazette of India Extraordinary Part II s.3(i). | 2025-11-13 | [MeitY / PIB — DPDP Rules 2025](https://static.pib.gov.in/WriteReadData/specificdocs/documents/2025/nov/doc20251117695301.pdf) | 2026-08-01 |
| Phase I — in force on notification | Provisions constituting and empowering the Data Protection Board (ss.18–26), definitions, and procedural rules took effect on 13 November 2025. | 2025-11-13 | [DPDP Rules 2025 (phased commencement)](https://static.pib.gov.in/WriteReadData/specificdocs/documents/2025/nov/doc20251117695301.pdf) | 2026-08-01 |
| Phase II — one year from notification | Section 6(9) (verifiable parental consent) and section 27(1)(d) (publication duty) commence one year from notification — November 2026. | 2026-11-13 | [DPDP Rules 2025 (phased commencement)](https://static.pib.gov.in/WriteReadData/specificdocs/documents/2025/nov/doc20251117695301.pdf) | 2026-08-01 |
| Phase III — substantive framework | Notice and consent standards, data fiduciary duties, children's data and data principal rights commence eighteen months from notification — May 2027. Published analyses split on 12 vs 13 May; confirm the exact day with counsel before relying on it. | 2027-05 | [DPDP Rules 2025 (phased commencement)](https://static.pib.gov.in/WriteReadData/specificdocs/documents/2025/nov/doc20251117695301.pdf) | 2026-08-01 |
| Penalty ceiling | The Schedule to the Act caps monetary penalties at up to ₹250 crore per instance for the highest tier (failure to take reasonable security safeguards to prevent a personal data breach), with lower tiers at ₹200 crore, ₹150 crore and below; the Data Protection Board determines penalties on the facts. | 2027-05 | [DPDP Act 2023, the Schedule (official Gazette text)](https://www.meity.gov.in/static/uploads/2024/06/2bf1f0e9f04e6fb4f8fef35e82c42aa5.pdf) | 2026-08-01 |
| Breach notification timeline (Rule 7) | Under Rule 7 of the DPDP Rules 2025, a data fiduciary must intimate the Data Protection Board of a personal data breach without delay on becoming aware, follow with a detailed report within 72 hours (extendable by the Board), and notify affected data principals of the breach in plain language. | 2027-05 | [DPDP Rules 2025, Rule 7](https://static.pib.gov.in/WriteReadData/specificdocs/documents/2025/nov/doc20251117695301.pdf) | 2026-08-01 |
| Notice contents (section 5) | Every consent request must be accompanied or preceded by a notice informing the data principal of: (i) the personal data and the purpose of processing; (ii) the manner of exercising rights under s.6(4) (withdrawal) and s.13 (grievance redressal); and (iii) the manner of making a complaint to the Data Protection Board. For consents given before commencement, notice must follow as soon as reasonably practicable. | 2027-05 | [DPDP Act 2023, section 5 (official Gazette text)](https://www.meity.gov.in/static/uploads/2024/06/2bf1f0e9f04e6fb4f8fef35e82c42aa5.pdf) | 2026-08-01 |

### EU AI Act

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Commencement and GPAI obligations | Regulation (EU) 2024/1689 entered into force on 1 August 2024. Governance rules and obligations for general-purpose AI (GPAI) model providers apply from 2 August 2025 (with transition for models already on the market). | 2025-08-02 | [EU AI Act — official text (EUR-Lex 2024/1689)](https://eur-lex.europa.eu/eli/reg/2024/1689/oj) | 2026-08-01 |

### GDPR

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Application date | Regulation (EU) 2016/679 entered into force 24 May 2016 and has applied across all EU member states since 25 May 2018. Breach notification to the supervisory authority is required without undue delay and, where feasible, within 72 hours (Art. 33). | 2018-05-25 | [GDPR — official text (EUR-Lex 2016/679)](https://eur-lex.europa.eu/eli/reg/2016/679/oj/eng) | 2026-08-01 |

### HIPAA (US)

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Security Rule compliance date | Compliance with the HIPAA Security Rule was required from 20 April 2005 for most covered entities; small health plans had until 20 April 2006. | 2005-04-20 | [US HHS — HIPAA Security Rule](https://www.hhs.gov/hipaa/for-professionals/security/laws-regulations/index.html) | 2026-08-01 |

### IRDAI

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Information and Cyber Security Guidelines, 2023 | IRDAI issued the Information and Cyber Security Guidelines, 2023 on 24 April 2023 — a data-centric, risk-based security framework for insurers and regulated intermediaries, superseding the 2017 guidelines. | 2023-04-24 | [IRDAI (official document)](https://irdai.gov.in/document-detail?documentId=3314780) | 2026-08-01 |

### IRDAI (ISNP)

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| ISNP audit duty | Insurance Self-Network Platforms require IRDAI permission (with pre-launch security testing) and an annual audit by an auditor holding a recognised IS-audit qualification (e.g. CISA, or CA with DISA); adverse findings affecting policyholders are reported to IRDAI with an action plan. | — | [IRDAI](https://www.irdai.gov.in/) | 2026-07-31 |

### IRDAI (India insurance)

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Information and Cyber Security Guidelines, 2023 | IRDAI issued the Information and Cyber Security Guidelines, 2023 on 24 April 2023 (ref IRDAI/GA&HR/GDL/MISC/88/04/2023), superseding the 2017 guidelines (IRDA/IT/GDL/MISC/082/04/2017) and three subsequent circulars. Scope extends beyond insurers to intermediaries including brokers, corporate agents, web aggregators, TPAs, ISNPs and IIB. | 2023-04-24 | [IRDAI - Information and Cyber Security Guidelines, 2023 (official document portal)](https://irdai.gov.in/document-detail?documentId=3314780) | 2026-08-02 |

### ISO 22301

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| 2019 revision publication | ISO 22301:2019 (business continuity management systems) was published 30 October 2019, replacing the 2012 first edition. | 2019-10-30 | [ISO 22301:2019 (iso.org)](https://www.iso.org/standard/75106.html) | 2026-08-01 |

### ISO/IEC 27001

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| 2022-revision transition deadline | The IAF three-year transition window for ISO/IEC 27001:2013 certificates ended 31 October 2025 — certificates not transitioned to the 2022 revision by that date lapsed. | 2025-10-31 | [ISO/IEC 27001 (iso.org)](https://www.iso.org/standard/27001) | 2026-08-01 |

### ISO/IEC 42001

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Publication | ISO/IEC 42001:2023 — the first AI management system (AIMS) standard — was published in December 2023 by ISO/IEC. | 2023-12 | [ISO/IEC 42001 (iso.org)](https://www.iso.org/standard/42001) | 2026-08-01 |

### NCA ECC (Saudi Arabia)

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Essential Cybersecurity Controls versions | Saudi Arabia's National Cybersecurity Authority first issued the Essential Cybersecurity Controls as ECC-1:2018; the updated ECC-2:2024 restructures the framework into 4 domains, 28 subdomains and 108 main controls, binding government entities and critical-infrastructure operators. | 2024 | [National Cybersecurity Authority (Saudi Arabia)](https://nca.gov.sa/en/) | 2026-08-01 |

### NIST CSF

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Version 2.0 release | NIST released Cybersecurity Framework 2.0 on 26 February 2024 — the first major revision since 2014, adding the Govern function and broadening applicability beyond critical infrastructure. | 2024-02-26 | [NIST (official release announcement)](https://www.nist.gov/news-events/news/2024/02/nist-releases-version-20-landmark-cybersecurity-framework) | 2026-08-01 |

### NPCI / UPI

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| TPAP guidelines - audit and data obligations (OC 97) | NPCI's Guidelines for Third-Party Application Providers in UPI (circular OC 97, 2020) impose audit and compliance obligations on TPAPs, including audits by CERT-In empanelled auditors and UPI data storage within India; PSP banks retain audit rights over TPAP UPI infrastructure. | — | [NPCI circular OC 97 - Guidelines for TPAPs in UPI (official PDF)](https://www.npci.org.in/PDF/npci/upi/circular/2020/OC-97-Guidelines-for-TPAPs-in-UPI.pdf) | 2026-08-02 |

### OWASP ASVS

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Current version | OWASP Application Security Verification Standard v5.0.0 (May 2025): ~350 requirements across 17 chapters, three verification levels (L1–L3). | 2025-05 | [OWASP ASVS project](https://owasp.org/www-project-application-security-verification-standard/) | 2026-08-01 |

### PCI DSS

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Current version | PCI DSS v4.0.1 is the current standard published by the PCI Security Standards Council. | — | [PCI SSC document library](https://www.pcisecuritystandards.org/document_library/) | 2026-08-01 |
| v4.x lifecycle dates | PCI DSS v3.2.1 retired 31 March 2024. v4.0.1 (a limited revision — no requirements added or removed) was published 11 June 2024, and v4.0 retired 31 December 2024, leaving v4.0.1 the only active version. The 51 future-dated v4.x requirements became mandatory in assessments from 31 March 2025. | 2025-03-31 | [PCI Security Standards Council (official blog)](https://blog.pcisecuritystandards.org/now-is-the-time-for-organizations-to-adopt-the-future-dated-requirements-of-pci-dss-v4-x) | 2026-08-01 |

### Qatar NIA (NCSA)

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| National Information Assurance Policy version | Qatar's National Cyber Security Agency mandates the National Information Assurance Policy for government entities and critical infrastructure; the current revision is v2.1 (May 2023), superseding v2.0. | 2023-05 | [NCSA Qatar (official portal)](https://ncsa.gov.qa/en/) | 2026-08-01 |

### RBI

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Payment system data storage in India | RBI circular DPSS.CO.OD No.2785/06.08.005/2017-2018 (6 April 2018) requires payment system providers to store the entire data relating to their payment systems only in India, with compliance within six months (by October 2018). End-to-end transaction data is covered. | 2018-10-06 | [Reserve Bank of India (circular DPSS.CO.OD No.2785/06.08.005/2017-2018)](https://www.rbi.org.in/) | 2026-08-01 |
| IT Governance Master Direction | Master Direction on Information Technology Governance, Risk, Controls and Assurance Practices (RBI/DoS/2023-24/107) issued 7 November 2023; effective 1 April 2024. Requires an IT governance framework, information/cyber security policies and periodic IT risk assurance for regulated entities. | 2024-04-01 | [Reserve Bank of India (Master Direction RBI/DoS/2023-24/107)](https://www.rbi.org.in/) | 2026-08-01 |
| IT Outsourcing Master Direction | Master Direction on Outsourcing of Information Technology Services (RBI/2023-24/102) issued 10 April 2023; effective 1 October 2023. Governs material IT outsourcing by regulated entities, including vendor risk, audit rights and concentration risk. | 2023-10-01 | [Reserve Bank of India (Master Direction RBI/2023-24/102)](https://www.rbi.org.in/) | 2026-08-01 |
| Digital Payment Security Controls Master Direction | Issued 18 February 2021: minimum security standards for digital payment channels — internet banking, mobile payments and card payments — binding scheduled commercial banks, small finance banks, payments banks and card-issuing NBFCs. | 2021-02-18 | [Reserve Bank of India (Master Direction, 18 Feb 2021)](https://www.rbi.org.in/) | 2026-08-01 |
| Cyber Security Framework in Banks | RBI’s Cyber Security Framework in Banks (2 June 2016) requires scheduled commercial banks to report cyber incidents to RBI within 2 to 6 hours of detection, alongside board-approved cyber security policy, SOC capability and cyber crisis management plans. | 2016-06-02 | [Reserve Bank of India (notification, 2 June 2016)](https://www.rbi.org.in/commonman/English/scripts/Notification.aspx?Id=1721) | 2026-08-01 |

### SAMA CSF (Saudi Arabia)

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Cyber Security Framework issuance | The Saudi Central Bank (SAMA) issued its Cyber Security Framework v1.0 in May 2017, applying to SAMA-regulated banks, insurers and finance companies; principle-based, drawing on ISO, Basel and PCI DSS. | 2017-05 | [SAMA — Cyber Security Framework (official PDF)](https://www.sama.gov.sa/en-US/Laws/BankingRules/SAMA%20Cyber%20Security%20Framework.pdf) | 2026-08-01 |

### SEBI CSCRF

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Issuance and compliance timeline | SEBI issued the Cybersecurity and Cyber Resilience Framework circular on 20 August 2024. Compliance timelines were extended more than once; for most regulated entities (excluding MIIs, KRAs and QRTAs) the final compliance date became 31 August 2025, with recurring half-yearly cyber-audit and reporting cycles thereafter. | 2024-08-20 | [SEBI — CSCRF FAQs (official PDF, June 2025)](https://www.sebi.gov.in/sebi_data/faqfiles/jun-2025/1749647139924.pdf) | 2026-08-01 |

### SWIFT CSP

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Programme and independent assessment | SWIFT launched the Customer Security Programme in 2016. Connected organisations attest annually against the Customer Security Controls Framework (CSCF, revised yearly), and from 2021 an independent assessment became mandatory for attestations rather than pure self-attestation. | 2021 | [SWIFT — Customer Security Programme (official)](https://www.swift.com/myswift/customer-security-programme) | 2026-08-01 |

### UAE PDPL

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| Enactment and effect | UAE Federal Decree-Law No. 45 of 2021 on the Protection of Personal Data was issued in 2021 and came into effect on 2 January 2022. The DIFC and ADGM financial free zones run their own data-protection regimes in place of the federal law. | 2022-01-02 | [UAE legislation portal / official summaries](https://u.ae/en/about-the-uae/digital-uae/data/data-protection-laws) | 2026-08-01 |

### UIDAI (Aadhaar)

| Fact | Value | Effective | Source | Verified |
|---|---|---|---|---|
| AUA / KUA audit duty | Authentication User Agencies and eKYC User Agencies must have operations audited annually (and on need) by a certified information systems auditor; the report is shared with UIDAI on request. | — | [UIDAI AUA/KUA Agreement (v4.0)](https://uidai.gov.in/images/resource/AUA_KUA_Agreement_v_40.pdf) | 2026-07-31 |

## Corrections

Found an error? Open an issue with the primary source. Confirmed corrections are appended to the changelog at the canonical registry — never silently edited. See our [editorial policy](https://cybersigmacs.com/editorial-policy/).

## Licence

[CC BY 4.0](LICENSE) — reuse, quote and redistribute with attribution to CyberSigma Consulting Services.