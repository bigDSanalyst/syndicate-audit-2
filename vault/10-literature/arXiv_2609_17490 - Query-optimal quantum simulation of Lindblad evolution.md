---
aliases: ["Query-optimal quantum simulation of Lindblad evolution"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.17490"
url: "http://arxiv.org/abs/2609.17490v1"
published: "2026-09-15T17:32:12Z"
ingested: "2026-09-16T10:49:46Z"
authors:
  - "Chunhao Wang"
  - "Christopher Ye"
---

# Query-optimal quantum simulation of Lindblad evolution

## Abstract

> For the problem of simulating Lindblad evolution for time $t$ to precision $ε$, Hamiltonian
> simulation provides an additive query lower bound, informally, $Ω(t + \mathrm{polylog}(1/ε))$.
> However, the best previously known algorithms for general Lindblad simulation achieve a
> multiplicative upper bound, informally, $\mathcal{O}(t\,\mathrm{polylog}(1/ε))$, in gate
> complexity. It has remained open whether this multiplicative dependence is necessary. In this
> paper, we close the gap in query complexity by giving an algorithm with optimal additive
> dependence on evolution time and precision in the block-encoding model. Our approach uses the
> transducer framework to reduce the query cost of composing first-order approximations to the
> evolution channel, together with linear combinations of reuse circuits of different lengths to
> suppress catalyst-removal error. Although our additional gate complexity is higher than that of
> existing algorithms, our optimal query complexity resolves the question of how much oracle
> access is fundamentally necessary and identifies the remaining challenge to achieve the optimal
> gate complexity.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

