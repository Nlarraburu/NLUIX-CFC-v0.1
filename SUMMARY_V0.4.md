# SUMMARY_V0.4.md

# NLUIX-CFC V0.4 — Coupling Parameter Sensitivity

## Objective

The purpose of V0.4 is to characterize how the NLUIX-CFC signal varies with the coupling parameter ξ.

## Method

Reference auxiliary field:

I(x) = 1 / (1 + ρ)

Configuration:

* Grid: 512³
* Seeds: 1, 2
* ξ ∈ {0.01, 0.03, 0.05, 0.10, 0.20}

For each run we measured:

* filtered ΔP/P
* local CFC correction amplitude
* correction standard deviation
* detected void count

---

## Results

### Filtered spectral response

|    ξ | Mean ΔP/P |
| ---: | --------: |
| 0.01 |   0.00168 |
| 0.03 |   0.00508 |
| 0.05 |   0.00854 |
| 0.10 |   0.01738 |
| 0.20 |   0.03601 |

### Local correction

|    ξ | Mean local signal |
| ---: | ----------------: |
| 0.01 |         1.40×10⁻⁴ |
| 0.03 |         4.21×10⁻⁴ |
| 0.05 |         7.01×10⁻⁴ |
| 0.10 |         1.40×10⁻³ |
| 0.20 |         2.81×10⁻³ |

---

## Interpretation

The measured observables scale almost linearly with ξ.

Examples:

0.05 → 0.10

ξ ×2

ΔP/P ×2.04

Local signal ×2.00

---

0.10 → 0.20

ξ ×2

ΔP/P ×2.07

Local signal ×2.00

---

The detected void population remains unchanged:

309.5 voids

for all tested values of ξ.

This indicates that ξ primarily controls signal amplitude rather than the underlying morphology of the simulated structure.

---

## Conclusion

The V0.4 study demonstrates that:

* the signal persists across all tested ξ values;
* the response is approximately linear over the interval 0.01 ≤ ξ ≤ 0.20;
* no instability or saturation is observed;
* ξ acts primarily as an amplitude parameter.

These results provide the first quantitative characterization of the coupling parameter within the NLUIX-CFC exploratory framework.
