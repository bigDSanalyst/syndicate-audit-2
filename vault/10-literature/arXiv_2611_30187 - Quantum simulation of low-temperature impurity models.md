---
aliases: ["Quantum simulation of low-temperature impurity models"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.30187"
url: "http://arxiv.org/abs/2611.30187v1"
published: "2026-11-23T07:31:07Z"
ingested: "2026-11-24T16:56:35Z"
authors:
  - "Jiaqing Jiang"
  - "Nathan Ju"
---

# Quantum simulation of low-temperature impurity models

## Abstract

> Quantum impurity models, which describe a small but strongly-interacting subsystem coupled to a
> large noninteracting bath, are the computational core of dynamical mean field theory and play an
> important role in simulating strongly correlated materials. We develop quantum algorithms for
> efficiently simulating these models at low temperatures and with high precision. For any
> impurity model on $n$ fermionic modes with fixed impurity size: (1) We give a quantum algorithm
> that prepares the thermal state at inverse temperature $β$ to precision $δ$ in time
> $\mathrm{poly}(n,β,\log(1/δ))$. This algorithm is the first to achieve both polynomial scaling
> in the inverse temperature and polylogarithmic scaling in the precision. When the Hamiltonian
> has an inverse-polynomial spectral gap, our quantum algorithm prepares its ground state to
> precision $δ$ in time $\mathrm{poly}(n,\log(1/δ))$. (2) We further give a quantum algorithm that
> prepares a purification of the thermal state in time $\mathrm{poly}(n,β,\log(1/δ))$. Using this
> purification, we estimate static and dynamical properties with error $δ$ in time polynomial in
> $n$ and $β$ and linear in $1/δ$ up to polylogarithmic factors, achieving the Heisenberg scaling.
> Our algorithms build on quantum Gibbs samplers, which are quantum analogues of Markov chain
> Monte Carlo methods. By using global jump operators instead of local ones, we avoid the
> $\exp(β)$ overhead commonly associated with quantum Gibbs samplers, making them efficient for
> impurity models even at low temperatures.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

