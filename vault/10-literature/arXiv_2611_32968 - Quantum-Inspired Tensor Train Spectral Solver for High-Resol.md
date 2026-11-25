---
aliases: ["Quantum-Inspired Tensor Train Spectral Solver for High-Resolution PDEs with Non-Periodic Boundary Conditions"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.32968"
url: "http://arxiv.org/abs/2611.32968v1"
published: "2026-11-24T17:05:00Z"
ingested: "2026-11-25T16:45:49Z"
authors:
  - "Sascha H. Hauck"
  - "Nis-Luca van Hülst"
  - "Matthias Kabel"
  - "Dieter Jaksch"
  - "Nicolas R. Gauger"
---

# Quantum-Inspired Tensor Train Spectral Solver for High-Resolution PDEs with Non-Periodic Boundary Conditions

## Abstract

> Tensor train (TT) methods enable high-resolution computational mechanics simulations by
> exploiting low-rank structure in discretized fields and operators. While the superfast Fourier
> transform (SFFT) has enabled efficient TT-based spectral solvers for periodic problems,
> corresponding representations for non-periodic boundary conditions remain underexplored. We
> introduce the superfast cosine and sine transforms (SFCT and SFST), extending the TT spectral
> framework to homogeneous Neumann and Dirichlet boundary conditions, respectively. Building on a
> quantum-circuit construction of the discrete cosine and sine transforms, we derive both
> transforms from a shared TT operator representation and prove that their TT ranks are bounded by
> $6r_S$, independently of the discretization order, where $r_S$ is the rank of the SFFT at the
> prescribed accuracy. The measured ranks plateau near 32 for grid sizes up to $2^{26}$ points.
> For Rayleigh-Bénard convection, spectral pressure projection achieves up to a 7-fold speedup in
> the Poisson solve relative to a preconditioned physical-space TT solver while maintaining
> comparable accuracy. Three-dimensional computational homogenization achieves a 2-6-fold speedup
> and a 4-7-fold reduction in memory consumption compared with the existing TT-based approach. The
> results establish an efficient TT framework for spectral PDE solvers with non-periodic boundary
> conditions.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

