---
aliases: ["Scaling H2 Factorization to Billion-Unknown Three-Dimensional Problems"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.30131"
url: "http://arxiv.org/abs/2610.30131v1"
published: "2026-10-21T17:59:12Z"
ingested: "2026-10-22T11:08:02Z"
authors:
  - "Tianyu Liang"
  - "Chao Chen"
  - "James Demmel"
  - "Yang Liu"
---

# Scaling H2 Factorization to Billion-Unknown Three-Dimensional Problems

## Abstract

> Strong recursive skeletonization provides approximate direct solvers for dense matrices from
> integral equations and kernel methods, but distributed implementations face substantial
> communication costs and limited parallelism, especially in three dimensions. We present a
> distributed-memory $\mathcal{H}^2$ factorization solver for symmetric matrices that combines
> spatial box coloring, delayed Schur complement updates, streamed sketching-based interpolative
> decomposition, and BLAS-3 and shared-memory kernels. Spatial coloring enables every process to
> participate in each boundary stage, while delayed updates and streamed sketching reduce dense
> storage and communication. To our knowledge, this is the first distributed-memory strong
> recursive skeletonization factorization demonstrated for three-dimensional volume integral
> equations at billion-unknown scale. Experiments on up to 512 compute nodes demonstrate
> factorization of a three-dimensional Laplace system with 3.62 billion unknowns, alongside three-
> dimensional Helmholtz tests and a two-dimensional Matérn system with 268 million unknowns.
> Combining streamed sketching and fully delayed updates reduces factorization time by $6.9\times$
> for Laplace and $8.5\times$ for Helmholtz relative to the unsketched, eager configuration, while
> reducing maximum per-process resident memory by 57\% and 54\%, respectively.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

