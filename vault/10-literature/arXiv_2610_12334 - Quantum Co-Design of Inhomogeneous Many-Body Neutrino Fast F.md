---
aliases: ["Quantum Co-Design of Inhomogeneous Many-Body Neutrino Fast Flavor Transformation"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.12334"
url: "http://arxiv.org/abs/2610.12334v1"
published: "2026-10-08T17:12:10Z"
ingested: "2026-10-09T12:32:52Z"
authors:
  - "Zoha Laraib"
  - "Sherwood Richers"
  - "Alessandro Baroni"
  - "Kathleen Hamilton"
  - "In-Saeng Suh"
---

# Quantum Co-Design of Inhomogeneous Many-Body Neutrino Fast Flavor Transformation

## Abstract

> Dense-neutrino flavor evolution is a quantum many-body problem whose fully correlated treatment
> becomes rapidly more expensive with increasing particle number and spatial structure. We develop
> a \texttt{QCNO} quantum simulation code that maps a inhomogeneous forward-scattering neutrino
> Hamiltonian with advection and finite-range interactions to TEBD2 product-formula quantum
> circuits, and connects ideal many-body simulation, backend-aware execution, and fault-tolerant
> resource estimation within the same physical model. We reproduce the exact many-body evolution
> of the suppressed mean-field-like transverse fast flavor instability through $N=30$ and show
> that even a single open-boundary interaction generates Rënyi entanglement and non-stabilizer
> magic, although noisy backends still produce polarization RMSEs of order $0.1$--$0.3$. The
> restricted active interaction graph of this problem allows us to estimate the circuit depth and
> $T$ gate cost through $N=50$ for both NISQ and fault-tolerant approaches. The measured TEBD2
> error in our fiducial ideal simulation of order $10^{-3}$ motivates a synthesis tolerance
> $\varepsilon_{\rm syn}\sim10^{-7}$, corresponding to about $70$ $T$ gates per $R_Z$ rotation.
> The generated circuit contains $1.4\times10^4$ $T$ gates per qubit for open boundaries (twice
> that for closed boundaries), requiring an application-level logical-$T$ error target of order
> $10^{-7}$ for early fault-tolerant architectures.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

