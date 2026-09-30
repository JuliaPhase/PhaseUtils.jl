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

This work has received funding from the Chips Joint Undertaking (JU) under grant agreement No 101111948 (14AMI). The JU receives support from the European Union's Horizon Europe research and innovation programme. The project is supported by the Chips Joint Undertaking and its members including the top-up funding by RVO (The Netherlands Enterprise Agency).

<img src="assets/funding/Chips-JU.png" alt="Chips Joint Undertaking, co-funded by the European Union" height="60">
