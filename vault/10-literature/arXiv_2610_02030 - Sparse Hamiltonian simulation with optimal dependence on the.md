---
aliases: ["Sparse Hamiltonian simulation with optimal dependence on the maximum column Euclidean norm"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.02030"
url: "http://arxiv.org/abs/2610.02030v1"
published: "2026-10-01T16:47:55Z"
ingested: "2026-10-02T11:51:27Z"
authors:
  - "Zecheng Li"
  - "Chunhao Wang"
---

# Sparse Hamiltonian simulation with optimal dependence on the maximum column Euclidean norm

## Abstract

> We give a quantum algorithm for simulating a $d$-sparse Hermitian Hamiltonian $H$, assuming a
> known upper bound $Λ$ on its maximum column Euclidean norm $\|H\|_{1\to2}$. For $tΛ\ge1/2$,
> simulation with operator-norm error $ε$ uses \[ O\!\left(tΛ\sqrt d+\sqrt d\log(2/ε)\right) \]
> sparse-oracle queries. This removes the subpolynomial overhead in Low's algorithm [STOC 2019],
> replacing it with an additive logarithmic precision term. For $d>1$ and $tΛ\ge\log(2/ε)$, the
> bound matches the worst-case lower bound. A known spectral-norm upper bound may also be used in
> place of $Λ$. The number of 1- and 2-qubit gates is linear in the query scale, up to oracle
> costs and polynomial overhead in the input bit lengths and logarithmic precision parameters. As
> applications, we obtain $O(κ\sqrt d\,\mathrm{polylog}(κ/ε))$ queries for solving $d$-sparse
> quantum linear systems with $\|A\|\le1$ and $\|A^{-1}\|\leκ$, under standard sparse and state-
> preparation access. We also give a gate-efficient implementation of black-box unitaries with at
> most $d$ nonzero entries per row and column using $O(\sqrt d\log(2/ε))$ queries, given sparse
> access to the unitary and its adjoint. At constant error, the query bound is optimal and yields
> $Θ(\sqrt N)$ queries for arbitrary $N\times N$ unitaries, resolving the open question on black-
> box unitary implementation posed by Berry and Childs [QIC 2012].

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

