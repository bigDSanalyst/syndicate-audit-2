---
aliases: ["Distributional Quantum Query Complexity"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.06835"
url: "http://arxiv.org/abs/2610.06835v1"
published: "2026-10-05T17:58:18Z"
ingested: "2026-10-06T12:43:40Z"
authors:
  - "Shalev Ben-David"
  - "M. H. Ebtehaj"
---

# Distributional Quantum Query Complexity

## Abstract

> Quantum query complexity enjoys a variety of pleasing joint computation properties: for example,
> a composition theorem asserting $Q(f\circ g)=Θ(Q(f)Q(g))$ for all Boolean functions $f$ and $g$;
> a direct sum theorem asserting that computing $k$ copies of a function (or search problem) costs
> $Ω(k)$ times as much as the cost of computing one copy; and a direct product theorem asserting
> that for Boolean functions, even succeeding at the direct sum problem with exponentially small
> probability still requires $Ω(k)$ times the cost of computing one copy to bounded error.
> However, all of these results are strictly for worst-case quantum query complexity. For example,
> if we have a fixed distribution $μ$ over inputs, the direct sum theorem says nothing about the
> quantum query complexity of computing $k$ copies of $f$ when the input comes from the product
> distribution $μ^k$ instead of being worst-case. (Note that while a standard Yao-type minimax
> theorem guarantees a hard distribution for the direct sum problem, there's no guarantee that
> this hard distribution is a product distribution.) A similar problem occurs for the direct
> product theorem and the composition theorem: none of these results respect distributions. In
> this work, we give distributional joint computation lower bounds for the composition, direct
> sum, and direct product problems. Along the way, we introduce some new tools for handling
> quantum query lower bounds, including (a) a new ``multiplicative'' variant of the $γ_2$ norm
> (which we use in place of the multiplicative adversary method for proving the direct product
> theorem), and (b) a new ``Shaltiel-free'' measure of quantum query complexity, which we show
> characterizes the composition behavior of distributional quantum query complexity and satisfies
> pleasing properties.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

