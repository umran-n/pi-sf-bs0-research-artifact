# PI-SF Methodology — Publication Companion Note

> **PI-SF selects the intelligence. PI-OS governs its operation.**

PI-SF is not designed to answer “What is the best model?”

It asks:

> **What is the best intelligence for this workflow, under these rules, costs, and failure tolerances?**

Conceptual selection form:

`(M*, θ*) = PI-SF(W, P, M_set)`

## Governance burden

The manuscript distinguishes semantic governance burden from reliability burden.

Conceptual semantic decomposition:

`B_semantic = B_repair + B_detect + B_suppress`

Where:

- `B_repair` = repair burden;
- `B_detect` = detection burden;
- `B_suppress` = suppression burden.

Reliability is treated separately as:

`B_rel`

These components are conceptual and are not empirically calibrated in BS-0.

## Native versus governed evidence

Paper 1 concerns native / ungoverned behavior. BS-0 does not establish PI-OS efficacy and does not qualify a candidate for deployment.

The next empirical layer is a paired governed evaluation under PI-OS controls, preserving the frozen workflow conditions and measuring Governance Delta relative to the native baseline.
