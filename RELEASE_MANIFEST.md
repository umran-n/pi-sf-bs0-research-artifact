# PI-SF BS-0 Publication Release Manifest

## Release identity

- Artifact: **PI-SF BS-0 Research Artifact**
- Intended release tag: `PI-SF-BS0-v1.0`
- Publication status: **pre-publication / private build**
- Associated paper: _Silence Is Not Clearance: Workflow-Specific LLM Selection for Institutional AI — A Seven-Model Study Using the Private Intelligence Selection Function (PI-SF)_
- Author: **Umran Nayani**

## Source authority

This curated artifact was derived from the private research repository:

`umran-n/pi-sf-deal-screener-benchmark`

Private reconciled source checkpoint:

`498a0c39fc71122b0a79f0b473d3e0898498d794`

Paper authority used for publication reconciliation:

**Candidate #003 — reconciled release candidate**

## Frozen empirical invariants

- Candidate models: **7**
- Cases: **7**
- Canonical observations: **49**
- Aligned: **24**
- Partial: **17**
- Misaligned: **8**
- DM-07: **0 Aligned / 0 Partial / 7 Misaligned**
- Technical aborts: **6**
- Non-canonical attempts: **2**
- Recorded inference events: **57**

No canonical observation was rescored during publication reconciliation.

## Public evidence authority

For the tagged release, the principal public evidence files are:

1. `corpus/BS0_FROZEN_CASES.md`
2. `results/BS0_CANONICAL_RESULT_LEDGER.csv`
3. `results/BS0_RESULT_MATRIX.md`
4. `results/BS0_CASE_LIBRARY.csv`
5. `results/BS0_MODEL_SUMMARY.csv`
6. `results/BS0_MODEL_ROSTER.csv`
7. `results/BS0_TECHNICAL_RETRY_LEDGER.md`
8. `results/FIREWORKS_PROVIDER_TOKEN_USAGE.csv`
9. `evidence/BS0_EVIDENCE_MANIFEST.md`
10. `methodology/BS0_NATIVE_PROTOCOL.md`
11. `methodology/PI-SF_Methodology.md`
12. `docs/DATA_DICTIONARY.md`

## Deliberate exclusions

The public artifact excludes private PI-OS engineering code, Control Tower notes, credentials, account identifiers, raw provider screenshots containing private UI/account data, private chain-of-thought/reasoning traces, and unrelated or unpublished experiments.

## Publication links

Interactive companion:

https://pi-os-guardians.lovable.app/

SSRN record:

**forthcoming**

Immutable GitHub release URL:

**to be bound after `PI-SF-BS0-v1.0` is created and the repository is made public**

## Final release gate

Before the repository is made public and tagged:

- [x] 49-cell ledger reconciles to 24 / 17 / 8
- [x] candidate-row totals reconcile to 24 / 17 / 8
- [x] case-row totals reconcile to 24 / 17 / 8
- [x] DM-07 remains 7 / 7 canonical failures
- [x] private-source checkpoint recorded
- [x] publication-safe methodology and evidence notes added
- [x] private reasoning/account-sensitive material excluded from curated package
- [ ] final repository content audit
- [ ] immutable tag `PI-SF-BS0-v1.0` created
- [ ] repository visibility changed to public
- [ ] immutable release URL inserted into paper and Lovable
- [ ] SSRN citation bound after publication
