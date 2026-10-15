---
aliases: ["CommerceGen-Studio: An End-to-End Framework for Commercial-Grade Main-Image Generation"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.20603"
url: "http://arxiv.org/abs/2610.20603v1"
published: "2026-10-14T17:59:48Z"
ingested: "2026-10-15T10:50:18Z"
authors:
  - "Xiaoli Xu"
  - "Zhengtao Wu"
  - "Zhengze Xu"
  - "Tao Liu"
  - "Yongchao Du"
  - "Zuan Gao"
  - "Xingjian Wang"
  - "Hao Yan"
  - "Mengting Chen"
  - "Wei Li"
  - "Bo Zheng"
---

# CommerceGen-Studio: An End-to-End Framework for Commercial-Grade Main-Image Generation

## Abstract

> We present CommerceGen-Studio, an end-to-end framework for generating commercial-grade main
> images for e-commerce Stock Keeping Units (SKUs). Our framework is organized along a three-stage
> pipeline of information extraction, semantic rewriting, and multi-condition generation: Prompt-
> Eval-Refine-Loop Agent (PERL-Agent) distills heterogeneous SKU metadata into concise selling-
> point text lists through an iterative closed loop of VLM and LLM roles scored by a reference-
> free rubric. Layout Thinker Optimization (LTO) aligns the rewriter with both caption and
> rendered-image quality via alternating domain-specific policy optimization. SKU-DiT, trained
> under Reinforce-Distill-Reinforce (RDR) progressive training, conditions jointly on the white-
> background product image, the trademark crop, and the structured layout to hold subject
> fidelity, trademark integrity, and character-level text accuracy together. The framework runs in
> production at a scale of millions of main images per day with a latency of a few seconds per
> image, which we believe makes it among the first systems of this kind to operate at commercial
> scale. We also release CommerceGen-Bench, a benchmark of hard cases collected from live traffic
> across all product categories. On it, our framework achieves the highest overall scores among
> the evaluated open-source baselines on both editing tracks, with and without prompt enhancement.
> It also matches much larger closed-source models, and beats several of them at Instruction
> Following and Product Integration - the two properties that determine whether an image can be
> published.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

