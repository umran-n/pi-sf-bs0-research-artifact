# BS-0 Evidence Manifest — Publication Artifact

## Private source authority

The structured public artifacts in this repository were derived from the higher-fidelity private BS-0 research record and reconciled to Paper 1 Candidate #003 before publication packaging.

Private source master evidence record:

`PIOS_BS0_FIREWORKS_NATIVE_BASELINE_v0_102.md`

Source-master SHA-256:

`E8BA7955C02E350FBD2597BE72E9E5B93F5651FC3AE2BAAA879D1997C5C66849`

The private source master is intentionally not included here because the public artifact is curated to exclude internal development state, account-sensitive material, and private reasoning traces.

## Canonical experiment state

- Primary candidates: **7 / 7 complete**
- Canonical cases per candidate: **7**
- Canonical native observations: **49 / 49**
- Aggregate observational coding: **24 Aligned / 17 Partial / 8 Misaligned**
- Preserved non-canonical operator/input attempts: **2**
- Preserved technical aborts: **6**
- Total recorded inference events: **57**
- DM-07 Silence Trap: **7 / 7 canonical observations failed**

The earlier aggregate `24 / 18 / 7` was a derived arithmetic/transcription error. No canonical observation was rescored.

## Frozen fixture hashes

| Case | SHA-256 |
|---|---|
| DM-01 | `E963D3BE059C6DD279A6A7E86BF85B6073D20EB9E48994BAC9C552911259EA0B` |
| DM-02 | `68F4DC5AF7D6C46584DC833B27EC97E1473CE123972F6ADB53FF2AD8401B8CBB` |
| DM-03 | `19A866C68164750AF8F93C0C773C8F72F8C4526F12106F2F26EF29C98AB442BC` |
| DM-04 | `3736C6EC027F6F35B9A4BA8E8437745666CA635FFD19AEFF79CC5F70C1BB7011` |
| DM-05 | `C77C8168D1B2D37C25DFA405573F2B1CC5F4382C1E56E5A151CAE94B14A7A6D8` |
| DM-06 | `CDC5D2AB97BAE0CC0349C6D42B615A2DF30BB83426898A5918673F2B086E562F` |
| DM-07 | `3579BB7805CFDE3C6D22A8F7BA930518562941E56BB1B44E350A71C76020652A` |

## Public structured artifacts

- `corpus/BS0_FROZEN_CASES.md`
- `results/BS0_CASE_LIBRARY.csv`
- `results/BS0_MODEL_ROSTER.csv`
- `results/BS0_CANONICAL_RESULT_LEDGER.csv`
- `results/BS0_MODEL_SUMMARY.csv`
- `results/BS0_RESULT_MATRIX.md`
- `results/BS0_TECHNICAL_RETRY_LEDGER.md`
- `results/FIREWORKS_PROVIDER_TOKEN_USAGE.csv`
- `results/FIREWORKS_PROVIDER_USAGE.md`
- `methodology/BS0_NATIVE_PROTOCOL.md`
- `methodology/PI-SF_Methodology.md`
- `docs/DATA_DICTIONARY.md`

## Excluded by design

This publication artifact does not include:

- private chain-of-thought or hidden reasoning traces;
- private PI-OS implementation repositories or control code;
- Control Tower working notes;
- raw account-identifying provider screenshots;
- credentials, secrets, or provider account identifiers;
- unrelated or not-yet-published experiments.

## Evidence boundary

The canonical result ledger and frozen fixture identities are the public behavioral evidence authority for this release. The interactive website is an explanatory companion and must not supersede the frozen artifact.
