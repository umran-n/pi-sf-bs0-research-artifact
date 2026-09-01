# BS-0 Research Data Dictionary

## Core identifiers

- `candidate_id` — frozen candidate identifier, `M-BS01` through `M-BS07`.
- `candidate` — model display name used in the study.
- `case_id` — frozen workflow case identifier, `DM-01` through `DM-07`.
- `run_id` — canonical one-shot run identity. Technical replacements retain explicit provenance in the run ID.

## Outcome fields

- `classification` — observational native classification: `ALIGNED`, `PARTIAL`, or `MISALIGNED`.
- `label` — fuller descriptive post-capture observation. It is not a qualification verdict.
- `expected_posture` — business expectation defined before model comparison and never shown to the model.

## Serving fields

- `ttft_ms` — provider-observed time-to-first-token in milliseconds, where captured.
- `throughput_tokens_s` — provider-observed generation throughput in tokens/second, where captured.
- `provider_token_usage` — Fireworks dashboard-observed token consumption. Provider values are rounded operational observations and are not exact model-level dollar-cost records.

These serving measures reflect the tested Fireworks configuration and are not end-to-end PI-OS latency measurements.

## Provenance fields

- `fixture_sha256` — SHA-256 identity of the exact frozen synthetic fixture.
- `technical_abort` — provider/model call that did not produce a valid final response; excluded from canonical behavior scoring but retained as reliability evidence.
- `non_canonical_attempt` — operator/input deviation preserved for provenance but excluded from the 49-cell primary matrix.

## State boundary

- `UNKNOWN` is an evidence state.
- `ADVANCE`, `HOLD`, and `DECLINE` are screening dispositions.
- A governance/control layer may `BLOCK` an attempted transition; `BLOCK` is not itself the paper-level screening disposition.

## Interpretation boundary

BS-0 fields characterize **native / ungoverned model behavior**. They do not constitute PI-OS model qualification or deployment authorization.
