---
aliases: ["Learning Native Reflection in Unified Models with Interleaved Reinforcement Learning"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.35767"
url: "http://arxiv.org/abs/2609.35767v1"
published: "2026-09-28T17:59:36Z"
ingested: "2026-09-29T12:06:21Z"
authors:
  - "Yijia Fan"
  - "Ziqi Huang"
  - "Zhongang Cai"
  - "Yan Li"
  - "Zimo Wen"
  - "Wanqi Yin"
  - "Haiwen Diao"
  - "Ziwei Liu"
---

# Learning Native Reflection in Unified Models with Interleaved Reinforcement Learning

## Abstract

> Unified multimodal models can both look at and render images, so in principle they can repair
> their own generations: diagnose what an image gets wrong, revise it, observe the result, and
> diagnose again. Whether a revision helps is known only after it is rendered, so the reflection
> text and the image generation must be learned jointly, over the whole loop. Supervised fine-
> tuning (SFT) on reflection trajectories gives a cold start but does not find the high-success
> repair paths, and naive RL that optimizes only the renderer or only one head leaves most of the
> gain untapped. We introduce UMM-Reflection, which applies reinforcement learning (RL) to
> complete reflection trajectories inside one unified model: sibling trajectories share one
> initial image, so the group-relative advantage compares reflection strategies, and one
> trajectory-level advantage updates both the reflection tokens and the flow-based revisions,
> avoiding the combinatorial blow-up of per-round credit assignment. Unlike single-round editing
> or pipelines with an external critic, credit flows across rounds and to both roles of the same
> model, and no verifier is needed at inference. On BAGEL, UMM-Reflection improves GenEval by
> 12.05 points over SFT, and the gains transfer to WISE (+10.97), OneIG-Bench (+3.48), and
> T2I-CompBench++ (+4.63), none of which is used in training.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

