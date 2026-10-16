---
aliases: ["Discovering state-of-the-art quantum circuits with large language models"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.22367"
url: "http://arxiv.org/abs/2610.22367v1"
published: "2026-10-15T17:59:20Z"
ingested: "2026-10-16T10:40:09Z"
authors:
  - "Andi Gu"
  - "Alek H. Kemeny"
  - "Susanne F. Yelin"
  - "Mikhail D. Lukin"
---

# Discovering state-of-the-art quantum circuits with large language models

## Abstract

> Significant efforts are currently being directed toward the implementation of large-scale
> quantum information processors, but realizing useful quantum advantage also requires the
> development of efficient quantum algorithms. While for many practical problems the dominant
> resource costs are associated with a small set of computational primitives, optimizing them in
> the quantum setting presents unique challenges, including a reversibility constraint absent from
> ordinary classical computation. Here we introduce an evolutionary framework in which large
> language models (LLMs) propose circuit designs and an independent evaluator verifies and scores
> them. We apply this framework to tasks spanning numerical computation, chemistry, optimization,
> quantum simulation, and number theory. In seven of the eight tasks, the discovered circuits
> significantly reduce both Toffoli and qubit counts relative to the state of the art. In the
> eighth, the search discovers a new reversible architecture for prime-field modular inversion. By
> handling reversibility differently, the architecture makes divsteps -- a classical algorithm
> previously impractical for reversible integer arithmetic -- viable and substantially improves
> the Toffoli-qubit trade-off for modular inversion. These results open the door for evaluator-
> guided LLM co-design of new algorithmic structures for quantum computation.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

