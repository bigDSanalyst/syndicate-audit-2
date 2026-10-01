---
aliases: ["Efficient Calculation of Equilibrium Correlation Functions"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.40349"
url: "http://arxiv.org/abs/2609.40349v1"
published: "2026-09-30T17:59:06Z"
ingested: "2026-10-01T12:24:55Z"
authors:
  - "Yizhi Shen"
  - "Roel Van Beeumen"
  - "Wibe A. de Jong"
  - "Efekan Kökcü"
---

# Efficient Calculation of Equilibrium Correlation Functions

## Abstract

> A majority of measurable dynamic quantities of a physical system is described as an equilibrium
> correlation function of the form $G_{AB}(t-t') = \left<A(t)B(t')\right>$, where $t'$ represents
> the impact time and $t$ represents the response time. Conventional quantum algorithms to compute
> such quantities via Hamiltonian simulation such as the Hadamard test, variational methods, or
> linear-response-based algorithms share one feature in common: each time point $t-t'$ is
> calculated by a different quantum circuit, leading to at least $O(N_t)$ total shots, and at
> least $O(N_t^2)$ total quantum gates. Here, we provide a different approach: utilizing $O(\log
> N_t)$ ancilla qubits to store time as a quantum variable, and effectively parallelize the
> computation of an equilibrium correlation function by requiring only a single quantum circuit
> for all time points. We show that this circuit needs to be run only $O(\log N_t)$ times, which
> in total requires $O(N_t \log N_t)$ quantum resources in the large system size limits. We prove
> that this scaling is optimal, and demonstrate our algorithm calculating the Green's function of
> a one-dimensional spinless Hubbard model.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

