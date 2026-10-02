---
aliases: ["A computational phase diagram for the transverse field Ising model"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.02079"
url: "http://arxiv.org/abs/2610.02079v1"
published: "2026-10-01T17:16:37Z"
ingested: "2026-10-02T11:51:27Z"
authors:
  - "Thuy-Duong Vuong"
---

# A computational phase diagram for the transverse field Ising model

## Abstract

> We study the transverse field Ising model, defined by the Hamiltonian $H =\frac{1}{2}\sum_{i,
> j\in [n]} J_{ij} Z_i Z_j +\sum_{i=1}^n h_i^z Z_i + η\sum_{i} X_i$ where $J $ is the symmetric
> interaction matrix, and $η$ is the transverse field strength. Let $Δ(J)=λ_{\max}(J)-λ_{\min}(J)$
> be the spectral width of $J.$ When the inverse temperature $β\geq0$ satisfies
> $Δ(J)\cdot\frac{\tanh(βη)}η\leq1$, we give a randomized classical algorithm that approximates
> the partition function $Z(β)=\operatorname{Tr}(e^{-βH})$ to a given relative error $ε\in(0,1)$
> in time polynomial in $n$, $β$, the model parameters, and $ε^{-1}$. When $ Δ(J) \cdot
> \frac{\tanh(βη)}η > 1 ,$ we show that approximating $ Z(β)$ within an
> $\exp(o(n))$-multiplicative factor is $\textbf{NP}$-hard, and thus unlikely to admit an
> efficient classical or quantum algorithms under standard complexity theoretic assumptions.
> Furthermore, in the regime $Δ(J)\cdot \frac{\tanh(βη)}η\leq 1,$ we provide an efficient
> randomized classical algorithm that approximates Pauli string observables of the Gibbs state $
> ρ_β= \frac{e^{-βH}}{\operatorname{Tr}(e^{-βH})}$ within an arbitrarily small additive error. In
> the special case when the observable is also diagonal in the $X$-basis, i.e. $P \in \{I,
> X\}^{\otimes n}$, the algorithm further achieves arbitrarily small relative error.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

