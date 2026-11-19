---
aliases: ["$Z$-sight: Unifying Vision-Language-Action and Latent World Modeling"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.24940"
url: "http://arxiv.org/abs/2611.24940v1"
published: "2026-11-18T18:59:38Z"
ingested: "2026-11-19T15:13:40Z"
authors:
  - "Junjie Ye"
  - "Yiqi Zhao"
  - "Muchen Xu"
  - "Celina Shiyu Wang"
  - "Hao Dong"
  - "Ruohai Ge"
  - "Rong Xue"
  - "Benjamin J Kolligs"
  - "Aditya Dutt"
  - "Sasanka Nagavalli"
  - "Nassim A. Samad"
  - "Gaurav S. Sukhatme"
  - "Jyotirmoy V. Deshmukh"
  - "Yue Wang"
  - "Yuliang Guo"
---

# $Z$-sight: Unifying Vision-Language-Action and Latent World Modeling

## Abstract

> We introduce $Z$-sight, a unified robot foundation model that couples vision-language-action
> (VLA) and generative latent world modeling. Video-based world action models (WAMs) show the
> value of joint future-and-action generation for control, yet inherit the heavy cost of video
> generators. Recent latent-space policies avoid pixel generation, yet typically align
> intermediate features or rely on frozen target encoders, decoupling future prediction from the
> VLM's native feature space. $Z$-sight instead predicts the future directly in the visual token
> space in which its VLM perceives the present. Coupling a foresight expert and a continuous
> action expert with the VLM in a mixture-of-transformers, $Z$-sight jointly denoises future
> spatial tokens and actions at inference without pixel reconstruction or external encoders.
> Trained on human video and robot trajectories, $Z$-sight achieves 81.9% success on SIMPLE (+9.6
> points over the strongest baseline) and 73.3% across six Unitree G1 tasks (+20.0 points) at 110
> ms per chunk, while remaining competitive on tabletop benchmarks.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

