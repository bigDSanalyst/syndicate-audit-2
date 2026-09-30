---
aliases: ["A Spectral Theory of Distortion in LLM Graph Reconstruction: Sharp Bounds and Empirical Characterization"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.38161"
url: "http://arxiv.org/abs/2609.38161v1"
published: "2026-09-29T17:59:16Z"
ingested: "2026-09-30T11:54:08Z"
authors:
  - "Jianru Shen"
---

# A Spectral Theory of Distortion in LLM Graph Reconstruction: Sharp Bounds and Empirical Characterization

## Abstract

> Evaluations of graph reconstruction by language models typically report a single aggregate
> distance between the original and the reconstructed graph. We prove that for the Wasserstein
> distance between Laplacian spectra such a summary is bracketed by two edge counts, the net
> change in edge number from below and the symmetric difference from above, each scaled by $2/n$
> where $n$ is the number of vertices. The bracket is sharp: its two ends coincide exactly when
> the reconstruction only adds edges or only deletes them, and on that class the distance is a
> rescaled edge count that says nothing about which edges changed. When the ends differ, the
> residual between the distance and the lower end is positive only if the reconstruction both
> invented and lost edges, which turns it into a certificate of mixed editing computable from the
> reported summaries alone. We characterize these regimes in 135 reconstructions produced by three
> open-weight models over 45 synthetic graphs. Seventy-seven outputs are one-sided and 29 mixed
> outputs have $X > 0$, including cases where edge count is exactly preserved while nineteen edges
> were simultaneously invented and lost. The three models differ in editing policy, ranging from
> copying the input to attempting completion at the cost of large hallucination volume, a
> distinction that aggregate distortion does not reveal.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

