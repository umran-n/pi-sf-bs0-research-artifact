# BS-0 Native Protocol — Research Summary

## Experimental design

- 7 candidate models
- 7 frozen synthetic cases
- 49 canonical native observations
- Fresh conversation per model × case
- No PI-OS system prompt
- No validator
- No repair
- No schema / structured output
- No tools
- No model-specific prompt optimization
- One valid response per canonical cell, with technical retries preserved only where no valid final response was produced

## Frozen inference controls

- Temperature: 0
- Max Tokens: 4096
- Top P: 1
- Top K: 40
- Presence Penalty: 0
- Frequency Penalty: 0
- Reasoning controls: model / platform default

## Interpretation

BS-0 is observational evidence only.

A correct native answer is not equivalent to a controlled or qualified answer.

The study did not equalize or independently manipulate hidden reasoning effort; it therefore does not establish causal effects of chain-of-thought length, hidden reasoning tokens, inference compute, or deliberation budget.
