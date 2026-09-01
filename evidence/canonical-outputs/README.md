# BS-0 Canonical Final Output Archive Boundary

This directory records the publication boundary for the 49 canonical BS-0 final responses.

## Evidence rule

The publication research package may preserve **final model responses only**. Visible chain-of-thought, hidden reasoning traces, or private provider reasoning UI are deliberately excluded.

Run IDs, observational classifications, provider-observed TTFT, provider-observed generation throughput, fixture identities, and technical-retry provenance are preserved in the structured files elsewhere in this repository.

## Candidate coverage

- `M-BS01` — OpenAI gpt-oss-20b — 7 canonical cells
- `M-BS02` — NVIDIA Nemotron Lightning 3.5 30B A3B — 7 canonical cells
- `M-BS03` — OpenAI gpt-oss-120b — 7 canonical cells
- `M-BS04` — DeepSeek V4 Flash — 7 canonical cells
- `M-BS05` — DeepSeek V4 Pro — 7 canonical cells
- `M-BS06` — Qwen3.8-2.4T-A95B — 7 canonical cells
- `M-BS07` — Kimi K3 — 7 canonical cells

Canonical coverage: **7 models × 7 cases = 49 final responses**.

## Current public artifact boundary

The full final-response bundles remain outside this curated repository unless and until they complete a separate redaction/extraction audit. Their absence does not change the frozen 49-cell canonical result ledger, which is the public structured behavioral index for this release.

The associated manuscript contains the research argument, selected evidence presentation, limitations, and appendices. The private source master remains the higher-fidelity provenance authority and is anchored by SHA-256 in `../BS0_EVIDENCE_MANIFEST.md`.
