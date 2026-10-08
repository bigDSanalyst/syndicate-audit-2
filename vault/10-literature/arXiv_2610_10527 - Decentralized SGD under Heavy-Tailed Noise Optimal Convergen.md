---
aliases: ["Decentralized SGD under Heavy-Tailed Noise: Optimal Convergence Rates and the Role of Gradient Clipping"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.10527"
url: "http://arxiv.org/abs/2610.10527v1"
published: "2026-10-07T17:57:58Z"
ingested: "2026-10-08T12:47:26Z"
authors:
  - "Aleksandar Armacki"
  - "Haoyuan Cai"
  - "Ali H. Sayed"
---

# Decentralized SGD under Heavy-Tailed Noise: Optimal Convergence Rates and the Role of Gradient Clipping

## Abstract

> Heavy-tailed noise has been widely observed in modern machine learning, motivating the use of
> methods like gradient clipping and normalization. While these methods are well understood in
> centralized settings, much less is known in decentralized ones, where applying a nonlinearity to
> local gradients affects both optimization and consensus. Recent works on decentralized non-
> convex optimization have studied both clipping and normalization under heavy-tailed noise, with
> clipping yielding suboptimal rates and normalization needing local momentum or mini-batches to
> converge. This raises the question: can a baseline decentralized method using a nonlinearity
> achieve optimal convergence rates under heavy-tailed noise? We answer affirmatively with clipped
> decentralized SGD ($\mathtt{DSGD}$). For smooth non-convex costs under bounded $p$-th moment
> noise, $p \in (1,2]$, we show that clipped $\mathtt{DSGD}$ achieves order-optimal rates both
> with high probability and in expectation. Moreover, we establish a linear speed-up in the number
> of agents, which, to our knowledge, has not been shown for decentralized methods with clipping.
> The key technical ingredient is a sharp analysis of the consensus gap that exploits the
> structure of clipping, relegating network effects to higher-order terms. Our results highlight
> an important distinction between clipping and normalization in decentralized settings: while
> normalized $\mathtt{DSGD}$ can fail to converge, clipping retains magnitude information,
> enabling $\mathtt{DSGD}$ to be convergent and order-optimal. Numerical experiments validate our
> theory.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

