---
aliases: ["Visual Tokens on Demand: Visual Budgeting for Scalable and Efficient Multi-Image Reasoning in Multimodal LLMs"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.18858"
url: "http://arxiv.org/abs/2610.18858v1"
published: "2026-10-13T17:59:24Z"
ingested: "2026-10-14T11:09:13Z"
authors:
  - "Aimon Rahman"
  - "Joymallya Chakraborty"
  - "Vidit Bansal"
  - "Abhishek Dan"
---

# Visual Tokens on Demand: Visual Budgeting for Scalable and Efficient Multi-Image Reasoning in Multimodal LLMs

## Abstract

> Multimodal large language models have advanced rapidly, but most remain optimized for single-
> image inputs. Multi-image reasoning is costly because each image adds many visual tokens,
> increasing encoding and attention demands. Existing techniques that address the above issue,
> including visual token pruning, token merging, visual token compression, learned resampling,
> hierarchical compression, retrieval-augmented visual reasoning, and memory-based architectures,
> have largely been designed for single-image scenarios, where redundancy is primarily spatial and
> local. Multi-image reasoning introduces additional challenges: redundancy may occur across
> images, task-relevant evidence may be sparse or distributed, and aggressive per-image
> compression can remove details needed for comparison, counting, temporal reasoning, retrieval,
> or evidence grounding. Moreover, existing token-reduction methods are often either (i) training-
> free but inference-inefficient, typically relying on accessing attention matrices to get token-
> importance that may be impractical to access with memory-efficient attention implementations
> such as FlashAttention, or (ii) training-dependent, requiring the base MLLM to be retrained or
> adapted to a new compressed-token paradigm. In this work, we study scalable multi-image
> reasoning and understanding without retraining the base model and without accessing attention
> matrices at inference time. To this end, we propose mmVB, a lightweight plug-and-play module
> that assigns query-conditioned per-image token budgets via cross-image context, adding only 1.6M
> trainable parameters while reducing visual input tokens by 9x. This reduction yields 5x faster
> time-to-first-token and 7x fewer prefill FLOPs, while maintaining 94.4% of full-resolution
> accuracy across eight multi-image reasoning benchmarks.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

