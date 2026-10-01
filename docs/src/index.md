# PhaseUtils.jl

Utilities for phase retrieval workflows. This documentation covers core helpers and shared data structures.

## Quickstart

```julia
using PhaseUtils

# Define a tilt with coefficients [σ, τ₁, τ₂]
t = TiltCentered([0.1, 0.2, -0.3])

# Evaluate on a small Fourier grid
A = materialize(t, (4, 4))
size(A)
```

## Learn more

- Guides
	- [Tilts and Axes](@ref guides/tilts_axes)
- Reference
	- [API](@ref api)

## Index
```@index
```

## Funding

This work is part of the 14AMI project (grant agreement No 101111948). The project is supported by the Chips Joint Undertaking and its members including the top-up funding by RVO (The Netherlands Enterprise Agency).

```@raw html
<img src="assets/funding/Chips-JU.png" alt="Chips Joint Undertaking, co-funded by the European Union" height="60" style="height: 60px; width: auto; margin-right: 1em;">
```
