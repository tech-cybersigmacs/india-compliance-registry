# CERT-In Directions Readiness Checklist

v1.0.0 · updated 2026-08-01 · Licence: CC BY 4.0 — reuse with attribution to CyberSigma
Sources: https://cybersigmacs.com/compliance-registry/ (entries certin-*)

## 1. Applicability and ownership

- [ ] Confirm you are in scope: the Directions bind service providers, intermediaries, data centres, body corporates and government organisations — there is no small-business exemption.
- [ ] Name a single owner for CERT-In compliance; the common failure is IT, security and legal each assuming another holds it.
- [ ] If you provide data-centre, VPS, cloud or VPN services, confirm the customer record-keeping duties (5 years post-cancellation) are on your register.

## 2. Six-hour incident reporting

- [ ] Map the reportable incident types from the Directions to your monitoring categories, so triage can recognise a reportable event.
- [ ] Authorise a named person (and an out-of-hours deputy) to DECIDE an incident is reportable — the window is lost in escalation, not detection.
- [ ] Pre-stage the CERT-In reporting channel and template; test the path end-to-end at least annually, including at night or on a weekend.
- [ ] Record 'time noticed' in your incident tooling — the six hours run from noticing, and you will need to evidence it.
- [ ] Check the same incident's parallel duties (DPDP breach notification, sector regulator) are triggered from ONE runbook, not three.

## 3. 180-day log retention, in India

- [ ] Inventory the ICT log sources in scope and confirm each retains a rolling 180 days.
- [ ] Verify the storage jurisdiction: logs retained long enough but in a non-India cloud region do not satisfy the Direction.
- [ ] Alert on collection failure — a silent gap discovered during an investigation is the expensive way to find it.

## 4. Time synchronisation

- [ ] Point servers, network devices and cloud workloads at NIC or NPL NTP sources (not public pools).
- [ ] Include container hosts and appliances — the evidential value of every log depends on consistent clocks.

## 5. Evidence and review

- [ ] Keep dated evidence for each item above (configs, retention reports, drill records) — assertion is not compliance.
- [ ] Re-verify after material change: cloud migration, new provider, new monitoring stack.
- [ ] Have the position independently assessed — CyberSigma is CERT-In empanelled, and many tenders require an empanelled auditor's report.

---
Maintained by CyberSigma (CERT-In empanelled, PCI QSA): https://cybersigmacs.com/open/cert-in-directions-checklist/