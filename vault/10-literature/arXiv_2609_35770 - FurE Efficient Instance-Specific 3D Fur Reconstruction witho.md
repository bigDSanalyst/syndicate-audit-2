---
aliases: ["FurE: Efficient Instance-Specific 3D Fur Reconstruction without Animal-Fur Datasets"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.35770"
url: "http://arxiv.org/abs/2609.35770v1"
published: "2026-09-28T17:59:58Z"
ingested: "2026-09-29T12:06:21Z"
authors:
  - "Srinjay Sarkar"
  - "Prakhar Kaushik"
  - "Soumava Paul"
  - "Alan Yuille"
---

# FurE: Efficient Instance-Specific 3D Fur Reconstruction without Animal-Fur Datasets

## Abstract

> Realistic and editable animal fur reconstruction from multi-view images is challenging due to
> fine-scale detail, self-occlusion and obfuscation, and, unlike human hair, the lack of animal-
> fur datasets. Fur usually covers most of an animal's body, with large inter-species and intra-
> species variability. We present FurE, an efficient strand-based animal fur reconstruction method
> that recovers a per-strand, editable groom by optimizing a root-conditioned latent field,
> decoded into strand geometry via a PCA-based decoder. We reconstruct a defurred animal body
> using local fur-thickness cues from a surface-constrained Gaussian Frosting representation
> together with part-based priors. We further show that a PCA-based decoder learned from human-
> hair strand data can alleviate animal-data scarcity while enabling substantially faster
> optimization. FurE achieves a 10x speedup in strand training over current SOTA dense per-strand
> optimization while retaining strand fidelity and generalizing across synthetic and real-world
> sequences, with quantitative and qualitative validation despite the reduction in training time.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

