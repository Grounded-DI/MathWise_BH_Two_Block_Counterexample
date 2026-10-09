# MathWise DI² — Two-Block Benjamini-Hochberg Counterexample

This repository preserves a seven-page Grounded DI LLC technical note dated 15 July 2026. It records a two-block, one-factor Gaussian construction in which ordinary Benjamini-Hochberg false-discovery-rate control exceeds its nominal level under correlated two-sided tests.

## Recorded mathematical result

The note states two fixed constructions:

- At `α = 0.01`, an outward-rounded certificate reports `lim inf FDR_N ≥ 0.01015553266461812931256738227976640877...`, strictly above `0.01`.
- For every fixed `α ∈ [0.00998, 0.01002]`, it reports `lim inf FDR_{N,α} ≥ αC` with `C > 1.00444096942730566742695824585628222635...`.

The note also records the Gaussian covariance reduction, threshold brackets, finite rectangle certificate, strict margins, and the pointwise-in-`α` quantifier. It expressly does not claim one common finite `N₀` for the entire interval.

## Evidence and provenance

The canonical artifact is [`Two_Block_BH_Grounded_DI_LLC.pdf`](Two_Block_BH_Grounded_DI_LLC.pdf), SHA-256 `c14ce198947ae1e500960c1f8d11259b1170e8a1066db78498effa069860ea64`. The PDF attributes this two-block note to Grounded DI LLC under the permission stated in the note; that permission does not assign authorship of the accompanying three-block preprint.

## Status and limitations

The PDF is a technical note and records internal recomputation of the analytic reduction and interval calculations. This checkout contains no executable verifier, raw Arb certificate files, or independent peer-review record. Accordingly, the mathematical statements are preserved as the note’s declared results; external independent validation remains **UNVERIFIED**.

The package addresses a specific two-block Gaussian construction and does not establish a universal failure of Benjamini-Hochberg, a general dependence theorem, or a production statistical control system.

## How to review

Read the abstract and Sections 1–2 for the construction and claims, then Sections 4–8 for the threshold certificate, numerical margins, reproducibility manifest, scope, and attribution.

Publisher: Grounded DI LLC


## Curated collection

This July 15, 2026 technical note is indexed in [MathWise Deterministic Replay Certificates](https://github.com/Grounded-DI/MathWise-Deterministic-Replay-Certificates/tree/main/bh-two-block-counterexample). This repository remains the canonical source; the later MPFR extension is indexed separately.
