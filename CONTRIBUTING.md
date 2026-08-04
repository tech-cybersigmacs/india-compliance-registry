# Contributing

This registry is useful only as long as every statement in it can be checked
against the body that issued it. That constraint drives everything below.

The canonical copy lives at <https://cybersigmacs.com/compliance-registry/>.
This repository is a mirror; `registry.json` is the machine-readable form and
`README.md` is generated from it.

## Reporting something wrong

Open an issue with the entry `id`, what it should say, and a link to the primary
source. Corrections are the most valuable contribution here — a wrong date in a
compliance reference is worse than a missing one, because someone may act on it.

## What counts as a source

Only the publication of the body that issued the rule:

- Gazette notifications, ministry PDFs (MeitY, MHA), PIB releases
- Regulator circulars — RBI, SEBI, IRDAI, UIDAI, NPCI, CERT-In
- Standards bodies for their own standards — PCI SSC, ISO, NIST

Not admissible: news coverage, consultancy blogs (including ours), summaries,
LinkedIn posts, or an AI assistant's account of any of the above. If the only
link available is secondary, the fact is not ready to be added.

## Entry rules

Validate against `schema.json` before opening a PR. Beyond the schema:

- **`value` must be checkable.** A reader should be able to open the source and
  confirm the statement without reading the whole document. Quote the operative
  clause or cite the section.
- **`lastVerified` means a human opened the source on that date** and saw the
  value there. It is not the date the file was edited. Do not advance it because
  a link checker returned 200.
- **`id` is a permanent identifier.** Third parties cite these. Never reuse an id
  for a different fact; retire it instead.
- **State what the source says, not what it implies.** Interpretation belongs in
  commentary, not in a registry entry.
- **Effective dates should be the date the obligation begins**, not the date of
  publication, where the two differ.

## Scope

Indian frameworks are the core: DPDP Act, CERT-In Directions, RBI, SEBI, IRDAI,
UIDAI, NPCI. A small number of international frameworks appear where Indian
organisations are routinely held to them (PCI DSS, ISO/IEC, SOC). Frameworks
with no Indian applicability are out of scope.

## Automated checks

CI validates `registry.json` against `schema.json`, rejects duplicate ids, and
requires every entry to carry an `https` source. A separate weekly job checks
that each source URL still resolves and flags entries not re-verified in 90
days; it cannot confirm that a document still says what it said, which is why
`lastVerified` remains a human judgement.

## Licence

Contributions are published under CC BY 4.0, the same terms as the registry.
