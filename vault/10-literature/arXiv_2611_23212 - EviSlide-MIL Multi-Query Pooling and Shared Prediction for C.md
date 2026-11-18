---
aliases: ["EviSlide-MIL: Multi-Query Pooling and Shared Prediction for Class-Incremental Whole-Slide Image Classification"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.23212"
url: "http://arxiv.org/abs/2611.23212v1"
published: "2026-11-17T18:50:42Z"
ingested: "2026-11-18T15:04:09Z"
authors:
  - "Zhouhan Qian"
  - "Sicheng Chen"
  - "Chad Wong"
  - "Tianyi Zhang"
  - "Enhui Chai"
  - "Zeyu Liu"
  - "Fei Xia"
---

# EviSlide-MIL: Multi-Query Pooling and Shared Prediction for Class-Incremental Whole-Slide Image Classification

## Abstract

> Histopathological analysis of whole-slide images (WSIs) plays a critical role in cancer
> diagnosis, and multiple instance learning (MIL) is widely adopted for WSI analysis under weak
> supervision. As new tumor subtypes are introduced, extending existing MIL models requires
> learning new classes while retaining knowledge of previously learned ones. This presents a
> class-incremental learning challenge, where models must acquire new classes with limited access
> to historical training data and recognize all learned classes without task identifiers at
> inference. A major obstacle is forgetting, as updates to feature aggregation and prediction
> modules can degrade performance on previously learned classes. To address this challenge, we
> propose \textbf{EviSlide-MIL}, a class-incremental WSI framework that integrates multiple
> learnable queries per class with a shared prediction module. The queries aggregate frozen patch
> features into class-specific representations, while the shared prediction module limits
> parameter growth across incremental stages. By freezing queries associated with previously
> learned classes, EviSlide-MIL preserves their attention patterns for identical inputs, while
> experience replay and knowledge distillation further mitigate forgetting as shared parameters
> are updated. Experiments on eight tumor subtypes from The Cancer Genome Atlas demonstrate that
> EviSlide-MIL achieves improved performance and reduced forgetting compared with competing
> methods across most learning settings, demonstrating its potential for scalable and knowledge-
> preserving WSI classification. Code and pretrained models will be released.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

