SUMMARY_V0.2.md
NLUIX-CFC V0.2 — Resolution-Aware Convergence Study
Objective

The purpose of V0.2 is to evaluate the numerical stability of the NLUIX-CFC mock cosmological framework when increasing spatial resolution while maintaining constant physical smoothing scales.

Unlike V0.1, where smoothing was defined in grid cells, V0.2 uses fixed physical scales:

Density smoothing: 15.625 Mpc/h
Auxiliary field smoothing: 11.71875 Mpc/h

This approach allows testing whether the CFC signal is a numerical artifact or persists under resolution refinement.

Method

Simulations were performed with:

ξ = 0.05
Seeds = 1, 2
Grid resolutions:
128³
256³
512³

For each run we measured:

filtered ΔP/P
local CFC correction amplitude
correction standard deviation
detected void count
Results
Grid	Mean ΔP/P filtered	Mean local CFC correction	Mean void count
128³	9.9×10⁻⁵	7.5×10⁻⁵	129.5
256³	2.48×10⁻⁴	9.4×10⁻⁵	251.0
512³	1.08×10⁻³	9.0×10⁻⁵	309.5
Interpretation

The filtered power-spectrum signal increases with resolution:

128³ → 0.00010

256³ → 0.00025

512³ → 0.00108

The signal therefore does not vanish under refinement.

In contrast, the mean local correction remains relatively stable across resolutions:

7.5×10⁻⁵ → 9.4×10⁻⁵ → 9.0×10⁻⁵

This suggests that local effects converge more rapidly than global spectral signatures.

The number of detected voids increases as expected with resolution, indicating improved structure identification.

Conclusion

The V0.2 study shows that:

the CFC signal persists under resolution refinement;
local correction amplitudes remain comparatively stable;
global spectral convergence is not yet achieved;
further investigation should focus on the definition of the auxiliary field I(x).

These observations motivate the V0.3 study, which explores alternative constructions of I(x).