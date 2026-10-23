---
aliases: ["Problem-aware sampling for bias and variance reduction in randomised Hamiltonian simulation"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.31515"
url: "http://arxiv.org/abs/2610.31515v1"
published: "2026-10-22T16:29:15Z"
ingested: "2026-10-23T10:59:07Z"
authors:
  - "Brian Coyle"
  - "Jonathan H. Fetherolf"
  - "Antonio Márquez Romero"
  - "Stefano Scali"
  - "Giuseppe Buonaiuto"
  - "Josh Kirsopp"
---

# Problem-aware sampling for bias and variance reduction in randomised Hamiltonian simulation

## Abstract

> Randomised quantum simulation algorithms such as qDRIFT reduce circuit depth by replacing
> deterministic product formulas with stochastic compilations, but achieving high accuracy can
> require many steps. In vanilla qDRIFT, Hamiltonian terms are sampled with probabilities
> proportional to their coefficient magnitudes. We propose StateDRIFT, a variant of qDRIFT which
> optimises its sampling distribution to estimate time-evolved quantities using knowledge of the
> initial state and target observable, with a provable truncation bound that keeps qDRIFT's
> guarantees. The distribution at each depth is chosen by solving an optimisation problem
> targeting bias and/or variance. StateDRIFT can significantly reduce the bias and variance of
> estimators, and hence circuit depth, which we test on short-time dynamics of lattice models and
> molecules under Jordan-Wigner up to 18 qubits. For example, with BeH2 StateDRIFT can reduce the
> number of two-qubit gates required to achieve a given accuracy from 11,201 to 983. StateDRIFT
> involves measuring observables and commutators on the initial state, so we propose two practical
> ways to estimate these: classical surrogates such as tensor networks, and classical shadows,
> which recover most or all of the saving from exact oracles in the systems tested.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

