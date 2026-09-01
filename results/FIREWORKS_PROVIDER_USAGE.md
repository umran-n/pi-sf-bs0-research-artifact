# Fireworks Provider-Side Usage Evidence

At the final provider-dashboard capture, Fireworks displayed:

- **Total serverless tokens:** 140.37K
- **Aggregate account spend:** $0.56
- **Credits remaining:** $5.44

Provider-observed token usage by candidate is recorded in `FIREWORKS_PROVIDER_TOKEN_USAGE.csv`. Dashboard values are rounded. The aggregate dollar meter is not a per-model cost allocation and must not be presented as such.

## Research use

This evidence supports an operational-resource layer alongside judgment results. In BS-0, greater token consumption did not monotonically correspond to stronger workflow suitability.

Notably, DeepSeek V4 Pro had the highest visible candidate token usage (33.8K) yet produced only one apparently aligned case, five partial cases, one misaligned case, and repeated technical aborts. Kimi K3 produced the strongest native judgment slate at 19.1K provider-observed tokens, while Nemotron remained the strongest observed throughput candidate at 21.4K provider-observed tokens.

> **Token consumption is an operational measure, not a direct measure of judgment quality.**

Raw dashboard screenshots are not included in this public artifact because the source captures contain account/interface identifiers. Publication-facing screenshots, if released separately, must remain privacy-cropped and are supplemental provider-interface evidence rather than behavioral authority.
