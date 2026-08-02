# India Incident-Reporting Map

v1.0.0 · updated 2026-08-01 · Licence: CC BY 4.0 — attribution to CyberSigma
Sources: https://cybersigmacs.com/compliance-registry/

| Who | Reports to | Clock | Detail |
|---|---|---|---|
| Everyone in scope of the CERT-In Directions | CERT-In | **6 hours from noticing** | Specified cyber incidents must be reported within six hours of being noticed. Applies to service providers, intermediaries, data centres, body corporates and government organisations — no small-business exemption. (registry#certin-6h) |
| Data fiduciaries (from DPDP Phase III, May 2027) | Data Protection Board + affected data principals | **Without delay, then 72-hour detailed report** | Rule 7: intimate the Board without delay on becoming aware; detailed report within 72 hours (extendable by the Board); notify affected data principals in plain language. Every personal data breach triggers the duty. (registry#dpdp-breach-notification) |
| Scheduled commercial banks | RBI | **2–6 hours from detection** | The Cyber Security Framework in Banks (2 June 2016) requires incident reporting to RBI within 2–6 hours of detection, with updates as facts develop. (registry#rbi-cyber-framework-2016) |
| SEBI regulated entities | Exchange / depository / SEBI per CSCRF category | **Per CSCRF reporting requirements** | The CSCRF (issued 20 Aug 2024) defines incident reporting through the entity's reporting authority; the cadence depends on your RE category — confirm against the framework text during scoping. (registry#sebi-cscrf-issued) |
| Insurers and intermediaries | IRDAI | **Per the 2023 guidelines** | The Information and Cyber Security Guidelines 2023 (24 Apr 2023) carry incident-reporting duties for regulated insurance entities; confirm the applicable timeline in the guidelines during scoping. (registry#irdai-infosec-2023) |

## The four traps

1. The clocks start at different moments: CERT-In runs from NOTICING, DPDP from BECOMING AWARE, RBI from DETECTION. Your incident log must timestamp each.
2. One runbook, not three: the most common failure is each duty living with a different team, and one filing being missed while another is being drafted.
3. Out-of-hours authority: six hours is lost in escalation, not detection — name who may classify an incident as reportable at 2am.
4. Evidence the filing: keep the submitted report, the timestamp and the acknowledgement — regulators ask for the trail, not the intention.

---
Maintained by CyberSigma (CERT-In empanelled, PCI QSA): https://cybersigmacs.com/open/india-incident-reporting-map/