# PCI DSS SAQ Eligibility Table

v1.0.0 · updated 2026-08-01 · Licence: CC BY 4.0 — attribution to CyberSigma
Authoritative criteria: https://www.pcisecuritystandards.org/document_library/ (your acquirer makes the final call)

| SAQ | Channel pattern | Who it is for | Watch out |
|---|---|---|---|
| **SAQ A** | E-commerce / MOTO, fully outsourced | Card-not-present merchants with ALL account data functions fully outsourced to PCI DSS validated third parties (hosted page, full redirect or compliant iframe). | Your systems must never touch card data; recent revisions tightened e-commerce page-security expectations. |
| **SAQ A-EP** | E-commerce, partially outsourced | E-commerce merchants whose website doesn't receive card data but controls how it is sent to the processor (direct post / JavaScript from your page). | Much heavier than SAQ A — your web environment is in scope. A full redirect/iframe integration is often cheaper than A-EP compliance. |
| **SAQ B** | Imprint / dial-out terminals | Merchants using imprint machines or standalone dial-out terminals only, no electronic storage. | Only while terminals are truly dial-out; moving to IP connectivity shifts you to B-IP. |
| **SAQ B-IP** | Standalone IP terminals | Merchants with standalone, PTS-approved terminals connected over IP, no electronic storage. | The terminals' IP path is in scope — segment it. |
| **SAQ C-VT** | Virtual terminal | Merchants keying one transaction at a time into a virtual terminal on an isolated workstation. | Eligibility hinges on isolation: dedicated workstation, no storage, no batch processing. |
| **SAQ C** | Connected POS / payment application | Merchants with POS or payment-application systems connected to the internet, no electronic storage. | Segmentation from the rest of the network is what keeps this scope from spreading. |
| **SAQ P2PE** | Validated P2PE hardware | Merchants using only hardware terminals from a PCI-listed, validated P2PE solution. | Only LISTED, validated P2PE solutions qualify — not any 'encrypting' terminal. |
| **SAQ D (Merchant)** | Everything else | All merchants not meeting a lighter SAQ's eligibility — including anyone storing account data electronically. | Before accepting SAQ D, scope: tokenisation, P2PE or outsourcing capture can move you to a far lighter SAQ. |
| **SAQ D (Service Provider)** | Service providers | Service providers eligible to self-assess; many acquirers and brands require a QSA-led ROC for larger providers instead. | Confirm early which path your customers and acquirers will actually accept. |

---
Interactive selector: https://cybersigmacs.com/pci-saq-selector/
Maintained by CyberSigma (PCI SSC-listed QSA): https://cybersigmacs.com/open/pci-saq-eligibility-table/