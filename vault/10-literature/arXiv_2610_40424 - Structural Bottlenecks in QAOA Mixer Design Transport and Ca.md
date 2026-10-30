---
aliases: ["Structural Bottlenecks in QAOA Mixer Design: Transport and Causal Reach"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.40424"
url: "http://arxiv.org/abs/2610.40424v1"
published: "2026-10-29T16:49:11Z"
ingested: "2026-10-30T12:06:49Z"
authors:
  - "Jasjyot Singh Gulati"
  - "Tharrmashastha SAPV"
---

# Structural Bottlenecks in QAOA Mixer Design: Transport and Causal Reach

## Abstract

> The choice of mixer is a central design decision in the Quantum Approximate Optimization
> Algorithm (QAOA), yet different structural limitations of a mixer need not be captured by a
> single metric. We identify two complementary structural bottlenecks for shallow QAOA:
> configuration-space transport, which limits how strongly probability can concentrate on high-
> quality solutions, and finite-depth causal reach, which limits which parts of a problem instance
> can influence a local objective term. In Part I, we derive first-order mixer-dependent objective
> bounds in complementary small-$β$ and small-$γ$ regimes. For connected regular mixer graphs, the
> two leading-order expressions are exactly equivalent through a graph-Laplacian identity and
> reduce to the same cost-weighted Dirichlet energy. We then derive a non-perturbative upper
> envelope from the layer-wise $\ell_1$ spreading of the mixer unitary, yielding a cost-
> distribution-dependent necessary spreading condition for attaining a target approximation ratio.
> In Part II, we study the locality bottleneck for MaxCut by augmenting the transverse-field mixer
> with problem-graph-aligned two-local interactions. The resulting $k$-hop construction has causal
> radius at most $(k+1)p$ at depth $p$; for the $k=1$ architectures studied numerically, this
> gives radius $2p$. Across cycles, circular ladders, and high-girth regular bipartite graphs,
> $X{+}XX$ and $X{+}YY$ improve the best-found approximation ratios over the standard $X$ mixer at
> equal depth, while $X{+}YY$ at depth $p$ comes within about one approximation-ratio point of
> plain $X$ at depth $2p$ in the reach-matched cases examined. The unequal performance of the
> equal-reach $XX$ and $YY$ augmentations shows that satisfying a structural capability does not
> by itself guarantee performance. Together, the results provide complementary structural insights
> for mixer design.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

