---
aliases: ["User Embeddings are Superpositions of Interpretable Behavioral Modes"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.08487"
url: "http://arxiv.org/abs/2611.08487v1"
published: "2026-11-05T18:59:42Z"
ingested: "2026-11-06T13:43:03Z"
authors:
  - "Jonathan Kozaczuk"
  - "Zheng Dong"
  - "Noyan Evirgen"
  - "Keivan Majidi"
  - "Eddie K. H. Ng"
  - "Chris Porter"
  - "Qi Zhao"
  - "Jia Geng"
  - "Changmao Li"
  - "Brandon R. Feng"
---

# User Embeddings are Superpositions of Interpretable Behavioral Modes

## Abstract

> User embeddings are central components of modern recommendation, personalization, and behavioral
> modeling systems. Though these embeddings can compactly encode rich behavioral information, they
> are inherently dense and opaque, limiting interpretability. To address this gap, we argue that
> user embeddings can be understood as sparse superpositions of interpretable behavioral modes.
> This structure is directly predicted by generative models of user behavior for linear embeddings
> and extends approximately to deep-learning representations by the superposition hypothesis.
> Superimposed modes can naturally be recovered by sparse dictionary learning methods, such as
> sparse autoencoders (SAEs), and recovered modes can be automatically named and queried in
> natural language. We validate mode recovery against known ground truth on synthetic data, where
> SAEs recover modes better than classical sparse baselines, including on transformer-encoded
> embeddings. We then apply the method to classical and transformer-based user embeddings from two
> real-world datasets. We also show how the corresponding natural-language labels enable zero-shot
> audience retrieval and characterization over embeddings never trained on text. The framework is
> post-hoc and model-agnostic, requiring no modification to the upstream embedding system.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

