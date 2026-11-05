---
aliases: ["Procedural Adversarial Learning"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.06890"
url: "http://arxiv.org/abs/2611.06890v1"
published: "2026-11-04T18:42:28Z"
ingested: "2026-11-05T13:58:04Z"
authors:
  - "Jack Nugent"
  - "Jia Deng"
---

# Procedural Adversarial Learning

## Abstract

> For many computer vision tasks, neural networks can be trained to produce a low average error,
> yet they still fail on seemingly simple scenes. Reducing these failures requires first finding
> them, but they may not be in a fixed dataset. We study procedural adversarial learning (PAL), a
> framework of minimax training and adversarial evaluation which searches the input space of a
> procedural generator for difficult instances. The procedural generator is an interpretable
> program mapping a low-dimensional vector of control parameters (e.g. layout, lighting, pose) to
> a rendered image and its label. We introduce the Simple-PAT algorithm, which uses zeroth-order
> optimization in the procedural generator's parameter space to propose adversarial training
> samples that are generated on demand. We also create PAL-Dojo, a collection of efficient
> procedural generators for surface normal estimation, image segmentation, and human pose
> estimation. Against a cross-model black-box adversary with 50M aggregate queries, Simple-PAT
> reduces worst-case error by a geometric mean of 3.15x compared to standard training and 2.63x
> compared to the strongest robust training baseline. Code is available at
> https://github.com/princeton-vl/procedural-adversarial-learning.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

