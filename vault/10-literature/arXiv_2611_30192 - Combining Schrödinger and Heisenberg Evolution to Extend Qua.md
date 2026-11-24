---
aliases: ["Combining Schrödinger and Heisenberg Evolution to Extend Quantum Many-Body Simulations"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.30192"
url: "http://arxiv.org/abs/2611.30192v1"
published: "2026-11-23T07:36:13Z"
ingested: "2026-11-24T16:56:35Z"
authors:
  - "Zhigang Hu"
  - "Igor Ermakov"
  - "Yauheni Talochka"
  - "Biao Wu"
  - "Oleg Lychkovskiy"
---

# Combining Schrödinger and Heisenberg Evolution to Extend Quantum Many-Body Simulations

## Abstract

> Classical simulations of quantum many-body dynamics face complementary limitations: entanglement
> growth restricts state evolution in the Schrödinger picture, while operator spreading makes
> Heisenberg-picture calculations increasingly expensive. Here, we combine both approaches by
> evolving quantum states and observables independently and joining their dynamics through
> massively parallel tensor-network contractions. We implement this strategy using tree tensor
> networks and sparse Pauli propagation, extending evolution times beyond those reached by either
> method separately in our calculations. For a quench of the two-dimensional transverse-field
> Ising model at the critical field, we simulate the magnetization of an $11\times11$ open lattice
> up to $t=1.20$ by combining state and operator evolution over intervals $t_S=t_H=0.60$. We
> compare the dynamics with iPEPS, numerical linked-cluster expansion, and X-truncated sparse
> Pauli dynamics results. We also combine exact state evolution on small clusters with operator
> propagation on a larger lattice, improving agreement with iPEPS relative to cluster evolution
> alone. We further derive error bounds showing how the state can suppress operator errors and the
> evolved observable can reduce sensitivity to state errors.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

