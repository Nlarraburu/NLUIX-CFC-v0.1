README_V0.2.md
NLUIX-CFC V0.2 — Resolution-Aware Convergence
[![DOI](https://zenodo.org/badge/1278371229.svg)](https://doi.org/10.5281/zenodo.20818638)

This folder contains the second convergence study of the NLUIX-CFC exploratory numerical framework.

Goal

Evaluate the stability of the CFC signal while keeping smoothing scales fixed in physical units.

Configuration

Parameter:

ξ = 0.05

Seeds:

1, 2

Resolutions:

128³

256³

512³

Physical smoothing scales:

Density field: 15.625 Mpc/h

Auxiliary field I(x): 11.71875 Mpc/h

Main Findings

The filtered ΔP/P signal increases with resolution:

128³ → 9.9×10⁻⁵

256³ → 2.48×10⁻⁴

512³ → 1.08×10⁻³

The mean local correction remains comparatively stable:

7.5×10⁻⁵

9.4×10⁻⁵

9.0×10⁻⁵

The signal therefore persists under refinement, although complete spectral convergence has not yet been reached.

Scientific Status

This repository presents an exploratory numerical experiment.

It is not a validated cosmological model and should not be interpreted as evidence for new physics.

The purpose of this work is to document reproducible numerical results and encourage open scientific discussion.

Next Step

V0.3 investigates alternative definitions of the auxiliary field I(x) in order to determine how the choice of field construction influences the observed signal.