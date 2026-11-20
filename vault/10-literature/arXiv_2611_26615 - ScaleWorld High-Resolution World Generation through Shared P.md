---
aliases: ["ScaleWorld: High-Resolution World Generation through Shared Prediction and Refinement"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.26615"
url: "http://arxiv.org/abs/2611.26615v1"
published: "2026-11-19T18:58:04Z"
ingested: "2026-11-20T14:52:15Z"
authors:
  - "Yansong Qu"
  - "Wesker Zheng"
  - "Quanjian Song"
  - "Zhiyuan Zhang"
  - "Xiao Cao"
  - "Shengchuan Zhang"
  - "Liujuan Cao"
---

# ScaleWorld: High-Resolution World Generation through Shared Prediction and Refinement

## Abstract

> High-resolution generation enables video world models to render fine-grained scene structures
> and textures, but directly generating high-resolution video incurs substantial computational and
> memory costs. We present ScaleWorld, a causal video model that unifies low-resolution world
> prediction and high-resolution refinement within a single shared backbone. By refining its own
> predictions, ScaleWorld produces high-resolution world videos without requiring a separate
> refinement model. For each video chunk, the shared backbone first completes a low-resolution
> prediction and then performs one-step high-resolution refinement conditioned on that prediction.
> To support efficient streaming generation, we maintain separate causal states with a long low-
> resolution history for prediction and a short high-resolution history for refinement. To address
> task interference during distillation, we separate specialist optimization from capability
> consolidation and introduce task-asymmetric on-policy distillation (TA-OPD). This procedure
> transfers prediction and refinement behaviors from specialized teachers into a shared student
> through local velocity matching under their respective sampling and history policies. {Extensive
> experiments demonstrate that ScaleWorld achieves high-quality world generation with improved
> computational and memory efficiency.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

