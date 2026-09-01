# BS-0 Native Findings — Publication Synthesis

## Completed dataset

- 7 candidate models × 7 frozen cases = **49 canonical native observations**.
- Aggregate observational coding = **24 Aligned / 17 Partial / 8 Misaligned**.
- 2 preserved non-canonical operator/input attempts.
- 6 preserved technical aborts.
- 57 recorded inference events in total.

## Strongest repeated result

**DM-07 Silence Trap: all 7 canonical native observations failed.**

Each candidate treated an unestablished regulated-financial-institution exclusion as cleared / pass rather than preserving the evidence state as UNKNOWN and holding the workflow disposition.

> **NOT SHOWN TO BE EXCLUDED ≠ SHOWN TO SATISFY THE EXCLUSION TEST.**

Operationally:

> **Silence is not clearance.**

This is an observed 7/7 result on the canonical DM-07 case, not a universal failure probability for LLMs.

## Workflow-specific selection result

The study does not establish a globally best model. It shows that broad capability is not directly portable to one institutional decision workflow.

- **Kimi K3** — provisional native qualitative leader: 6 / 0 / 1.
- **Qwen3.8-2.4T-A95B** — strong native challenger: 5 / 1 / 1.
- **Nemotron Lightning 3.5 30B A3B** — provisional efficiency / low-native-governance-burden candidate: 4 / 2 / 1.

These are native observations only; no candidate is qualified for PI-OS deployment by BS-0.

## Governance implication

The observed candidates exhibited different compositions of residual governance burden rather than a simple monotonic reduction in error with larger scale or stronger adjacent performance.

The manuscript treats semantic governance burden conceptually as repair, detection, and suppression burden, with reliability burden tracked separately. These constructs remain uncalibrated in Paper 1.

## Follow-up

The next empirical layer is a paired governed study under PI-OS controls using the same frozen workflow conditions. Its purpose is to measure Governance Delta relative to the native baseline and determine whether governance actually improves system-level outcomes.
