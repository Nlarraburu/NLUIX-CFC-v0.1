# README_V0.4.md

# NLUIX-CFC V0.4 — Xi Sensitivity Study
[![DOI](https://zenodo.org/badge/1278371229.svg)](https://doi.org/10.5281/zenodo.20818638)

This study investigates how the NLUIX-CFC signal depends on the coupling parameter ξ.

Previous releases established:

* V0.1 — Initial signal detection
* V0.2 — Resolution-aware convergence study
* V0.3 — Auxiliary field I(x) variants

V0.4 focuses on the response of the model to variations of ξ.

## Reference configuration

Auxiliary field:

I(x) = 1 / (1 + ρ)

Selected after the V0.3 study as the reference implementation.

Simulation setup:

* Resolution: 512³
* Seeds: 1, 2
* ξ values:

  * 0.01
  * 0.03
  * 0.05
  * 0.10
  * 0.20

## Main Results

|    ξ | Mean ΔP/P filtered | Mean local signal |
| ---: | -----------------: | ----------------: |
| 0.01 |            0.00168 |         1.40×10⁻⁴ |
| 0.03 |            0.00508 |         4.21×10⁻⁴ |
| 0.05 |            0.00854 |         7.01×10⁻⁴ |
| 0.10 |            0.01738 |         1.40×10⁻³ |
| 0.20 |            0.03601 |         2.81×10⁻³ |

## Main Finding

The local signal, filtered spectral response and correction standard deviation scale approximately linearly with ξ over the explored range.

No saturation or instability is observed.
The detected void population remains constant across the explored parameter range (309.5 mean voids), suggesting that ξ modifies signal amplitude without significantly affecting large-scale morphology.

## Scientific disclaimer

NLUIX-CFC is an exploratory numerical experiment.

It is not a validated cosmological model and should not be interpreted as evidence for new physics.

The purpose of this repository is to document reproducible numerical results and encourage open scientific discussion.
