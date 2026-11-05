---
aliases: ["A Tensor-Network Chebyshev--Galerkin Method for Boundary-Value Problems in Computational Mechanics"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.06552"
url: "http://arxiv.org/abs/2611.06552v1"
published: "2026-11-04T14:16:51Z"
ingested: "2026-11-05T13:58:00Z"
authors:
  - "Juan José Rodríguez-Aldavero"
  - "Ángel de la Rosa Velasco"
  - "Juan José García-Ripoll"
---

# A Tensor-Network Chebyshev--Galerkin Method for Boundary-Value Problems in Computational Mechanics

## Abstract

> Quantum-inspired numerical methods for partial differential equations represent discretized
> fields and operators as quantics tensor trains (QTT), so that their cost depends on how
> compressible the problem is rather than on the number of unknowns. Global spectral formulations
> in this setting have so far relied on Fourier bases, restricted to periodic problems, or on
> collocation, which does not preserve the variational structure exploited by tensor-network
> solvers. We introduce a QTT Chebyshev--Galerkin method that assembles and solves global spectral
> systems directly in compressed form, without forming the underlying arrays. Starting from the
> weak formulation, the method handles coupled elliptic systems with variable coefficients,
> smoothly mapped geometries, and mixed Dirichlet--Robin boundary conditions, and yields symmetric
> positive-definite systems suited to variational tensor-network solvers. Parameters and random
> inputs enter as additional coordinates, so the same construction returns the solution over an
> entire parameter space in a single solve. In linear elasticity, the method retains spectral
> convergence and reaches errors below $10^{-8}$ on a three-dimensional benchmark, beyond those
> attained by QTT finite differences and Q2/Q4 FEniCSx finite elements over the tested range. A
> six-parameter cantilever design study covering $1.7\times10^{7}$ designs is solved in a single
> 92~s run, and a stochastic problem with ten random coordinates is represented with
> $2.4\times10^{6}$ times less memory than its full coefficient array.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

