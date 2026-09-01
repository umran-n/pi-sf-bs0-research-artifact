# PI-SF BS-0 Public Release Audit

**Audit date:** 2026-09-01  
**Artifact:** `umran-n/pi-sf-bs0-research-artifact`  
**Audit stage:** public pre-tag freeze

## Disposition

**CONTENT PACKAGE: PASS**  
**PUBLIC VISIBILITY: PASS**  
**IMMUTABLE RELEASE: HOLD pending tag + GitHub Release**

## Empirical reconciliation

PASS.

- 7 candidates × 7 cases = 49 canonical observations.
- Candidate rows independently reconcile to 24 Aligned / 17 Partial / 8 Misaligned.
- Case rows independently reconcile to 24 / 17 / 8.
- Canonical result ledger independently reconciles to 24 / 17 / 8.
- DM-07 remains 0 Aligned / 0 Partial / 7 Misaligned.
- No canonical observation was rescored during publication packaging.
- 6 technical aborts and 2 non-canonical attempts remain separate from the 49-cell scoring matrix.
- 49 + 6 + 2 = 57 recorded inference events.

## Frozen-case identity

PASS.

All seven fixture SHA-256 identities are preserved in both the frozen corpus and case library.

## Claim boundary

PASS.

The curated package:

- identifies BS-0 as native / ungoverned observational evidence;
- does not qualify any candidate for deployment;
- does not claim PI-OS efficacy;
- treats the DM-07 7/7 result as an observed canonical result rather than a universal LLM failure probability;
- preserves UNKNOWN as an evidence state and HOLD as the associated screening disposition for unresolved mandatory exclusion evidence;
- treats Governance Burden components as conceptual / uncalibrated;
- distinguishes reliability burden from semantic governance burden;
- avoids causal claims from parameter scale or hidden reasoning effort;
- labels serving metrics as provider-observed and environment-relative.

## Privacy / publication boundary

PASS for the curated package.

The repository tree intentionally excludes:

- credentials and secrets;
- raw account-identifying provider screenshots;
- private chain-of-thought or hidden reasoning traces;
- Control Tower notes;
- private PI-OS implementation code;
- unrelated or unpublished experiments.

The private source-master identity is anchored by SHA-256 without publishing the private source master itself.

## Provenance

PASS.

Private reconciled source repository checkpoint:

`umran-n/pi-sf-deal-screener-benchmark`

`498a0c39fc71122b0a79f0b473d3e0898498d794`

Publication manuscript authority:

**Candidate #003 — reconciled release candidate**

## Repository package inventory

The curated release contains:

- publication README and navigation;
- frozen seven-case corpus;
- canonical 49-observation result ledger;
- reconciled result matrix;
- case library;
- model roster and summary;
- technical retry / non-canonical provenance ledger;
- provider-observed token usage and bounded usage note;
- publication findings and case-level synthesis;
- native selection note;
- BS-0 protocol;
- PI-SF methodology note;
- data dictionary;
- structured reproducibility guide;
- evidence manifest;
- canonical-output publication boundary;
- citation metadata;
- rights / reuse boundary;
- release manifest;
- release checklist;
- changelog.

## Remaining release operations

1. Create immutable tag `PI-SF-BS0-v1.0` pointing at the frozen publication commit.
2. Create a GitHub Release from that tag.
3. Record the immutable release URL.
4. Bind that URL into the manuscript and Lovable companion.
5. After SSRN publication, bind the canonical SSRN record into this repository and the companion site without changing the frozen empirical files.

## Mutation rule after freeze

Once `PI-SF-BS0-v1.0` is tagged, the tagged release is immutable publication authority.

Future corrections or metadata bindings must use a new commit and, if empirically material, a new tagged release. The `PI-SF-BS0-v1.0` tag must not be silently moved.
