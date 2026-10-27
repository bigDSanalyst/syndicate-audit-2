---
aliases: ["OSWAM: An Effective World Action Model with One-Step Action Generation"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.35850"
url: "http://arxiv.org/abs/2610.35850v1"
published: "2026-10-26T17:57:09Z"
ingested: "2026-10-27T11:35:02Z"
authors:
  - "Guowen Zhang"
  - "Liyi Chen"
  - "Xu Hu"
  - "Pengfei Wang"
  - "Jingfan Chen"
  - "Chenhang He"
  - "Lei Zhang"
---

# OSWAM: An Effective World Action Model with One-Step Action Generation

## Abstract

> Direct-policy World Action Models (WAM) have demonstrated the benefits of decoupling action
> generation from explicit future visual prediction for efficient inference in autonomous driving
> and embodied control. However, they still require tens of denoising steps to achieve competitive
> action quality, incurring substantial latency and hindering real-time deployment. Simply
> reducing the number of denoising steps will collapse the nonlinear multi-step denoising
> trajectory into coarse updates, substantially degrading action quality. To reduce the denoising
> steps while enabling real-time action generation, we present an effective world action model
> with one-step action generation, namely OSWAM, for autonomous driving and embodied control. We
> argue that it is the absence of structured action priors in random noise initialization that
> forces direct-policy WAMs to recover coherent action sequences through iterative denoising.
> Hence, we construct imagination tokens to initialize the diffusion process, providing physical
> priors and action-conditioned representations. We further introduce privileged information
> distillation with future conditioning to enhance future-aware action generation. As a result,
> OSWAM can efficiently and effectively generate high quality actions in just one diffusion step.
> Our experiments demonstrate that OSWAM achieves comparable or even better results in both
> autonomous driving and embodied control than direct-policy WAM and Joint-WAM that require tens
> of steps. It obtains approximately $3\times$ speedup over direct-policy WAM baselines and
> supports real-time compiled inference with latency as low as 40ms on an NVIDIA RTX 5090 GPU. The
> project page is available at https://gwenzhang.github.io/OSWAM/

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

