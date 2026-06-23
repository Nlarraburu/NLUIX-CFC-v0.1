# NLUIX-CFC V0.2 — Resolution Study

## Objective

Evaluate the robustness of the CFC signal when increasing numerical resolution while keeping physical smoothing scales fixed.

## Tested resolutions

- 128³
- 256³
- 512³

Parameters:

- xi = 0.05
- 2 independent seeds per resolution
- physical smoothing scales preserved

## Results

| Grid | Mean filtered ΔPk/Pk | Mean local CFC signal | Mean void count |
|--------|--------|--------|--------|
| 128³ | 9.9×10⁻⁵ | 7.5×10⁻⁵ | 129.5 |
| 256³ | 2.48×10⁻⁴ | 9.4×10⁻⁵ | 251.0 |
| 512³ | 1.08×10⁻³ | 9.0×10⁻⁵ | 309.5 |

## Interpretation

The filtered spectral response increases significantly with numerical resolution.

No spectral convergence is observed between 128³ and 512³.

In contrast, the local CFC signal measured around voids remains remarkably stable between 256³ and 512³.

## Conclusion

The global spectral response is resolution dependent and not yet converged.

The local void signal appears substantially more robust and survives the increase in numerical resolution.

These results motivate further investigation of local observables rather than relying solely on global power-spectrum statistics.