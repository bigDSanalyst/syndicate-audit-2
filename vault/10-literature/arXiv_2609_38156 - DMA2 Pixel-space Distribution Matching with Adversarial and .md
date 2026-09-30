---
aliases: ["DMA$^2$: Pixel-space Distribution Matching with Adversarial and Anchor Losses"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.38156"
url: "http://arxiv.org/abs/2609.38156v1"
published: "2026-09-29T17:59:03Z"
ingested: "2026-09-30T11:54:08Z"
authors:
  - "Xin Lin"
  - "Zhifei Zhang"
  - "Yuqian Zhou"
  - "Haitian Zheng"
  - "Shaoteng Liu"
  - "Lehan Yang"
  - "Zhe Lin"
  - "Ming-Hsuan Yang"
  - "Truong Nguyen"
---

# DMA$^2$: Pixel-space Distribution Matching with Adversarial and Anchor Losses

## Abstract

> Distribution matching distillation (DMD) provides a general framework for few-step diffusion
> generation, but its modern text-to-image instantiations have been developed primarily around
> latent diffusion. It therefore overlooks key properties and design opportunities of native RGB.
> We revisit two DMD interfaces for pixel-space teachers. On the teacher-matching side,
> diagnostics show low-noise RGB matching is dominated by a local-texture cue, motivating a fixed
> high-noise matching band. On the real-data side, native clean-RGB outputs allow guidance from an
> external visual representation without traversing a decoder or sharing the heavy fake-score
> critic. DINO-Adv removes this critic from the adversarial gradient path and supplies local
> parametric patch guidance. For distribution-level guidance, we introduce AF-Loss, a parameter-
> free auxiliary semantic distribution-field objective designed for text-to-image DMD. It operates
> on detached rolling real and generated supports in the shared DINOv2 space while preserving
> prompt-conditioned teacher supervision. AF-Loss adds no learnable parameters or inference-time
> computation. Together these designs form DMA$^2$. Across DPG-Bench, GenEval, VQAScore, and
> COCO30K, the four-step DMA$^2$ student performs better than the 25-step teacher and evaluated
> few-step distillers.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

