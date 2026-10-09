---
aliases: ["A deterministic polynomial chaos Galerkin method for non-Markovian quantum state diffusion"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.12070"
url: "http://arxiv.org/abs/2610.12070v1"
published: "2026-10-08T14:48:29Z"
ingested: "2026-10-09T12:32:52Z"
authors:
  - "Quanhui Zhu"
  - "Zhenning Cai"
---

# A deterministic polynomial chaos Galerkin method for non-Markovian quantum state diffusion

## Abstract

> Developing general-purpose numerical methods for non-Markovian quantum state diffusion has long
> been a challenge in the simulation of open quantum systems. This paper proposes a deterministic
> polynomial chaos Galerkin method, which is easy to implement, accurate, and efficient. By
> combining a low-rank decomposition of bath correlations with Galerkin projection onto a
> polynomial chaos basis, the method yields a deterministic formulation compatible with standard
> numerical solvers for partial differential equations. The reduced density matrix is obtained
> from a single deterministic solve at a cost comparable to that of computing one stochastic
> hierarchy trajectory. Replacing an ensemble of $N_{\mathrm{traj}}$ trajectories therefore
> reduces the computational cost by approximately a factor of $N_{\mathrm{traj}}$ and eliminates
> statistical sampling error. Benchmark comparisons show that the proposed method achieves smaller
> errors at lower computational cost than the tested stochastic hierarchy methods. Applications
> involving nonquadratic potentials, diffraction and interference, and coupled three-dimensional
> dynamics demonstrate its ability to handle challenging problems.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

