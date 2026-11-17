---
aliases: ["FaceJev: Direct Visual Decisions for Face Forgery Detection"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.21604"
url: "http://arxiv.org/abs/2611.21604v1"
published: "2026-11-16T18:59:04Z"
ingested: "2026-11-17T15:28:29Z"
authors:
  - "Siran Peng"
  - "Tianshuo Zhang"
  - "Yibo Xue"
  - "Ajian Liu"
  - "Haoyuan Zhang"
  - "Weisong Zhao"
  - "Shuhuan Chen"
  - "Xiangyu Zhu"
  - "Zhen Lei"
---

# FaceJev: Direct Visual Decisions for Face Forgery Detection

## Abstract

> Face forgery detection methods often perform well on seen manipulations but generalize poorly to
> unseen ones. Multimodal Large Language Models (MLLMs) can recognize facial parts and assess
> their visual plausibility. Existing MLLM-based methods typically express these judgments through
> textual explanations, but seldom treat individual part decisions as explicit learning targets.
> We present FaceJev, an MLLM-based method for face forgery detection through direct visual
> decisions. Following the Jev formulation, FaceJev answers eight independent questions about
> facial parts using a shared image encoding and reads anomaly probabilities from the native
> answer logits. A face is classified as forged if any part is predicted to be abnormal, directly
> linking the detection result to the part decisions. We construct PartForensics, a dataset of
> approximately 160k images with binary anomaly targets for the eight facial parts, to supervise
> these decisions. We further propose FS-GRPO, which optimizes each part decision through an exact
> reward comparison with its alternative, using both detection and part rewards. FaceJev
> outperforms the strongest baseline by 7.25 percentage points on unseen manipulations. Extensive
> ablation studies validate our design choices and the effectiveness of the main components.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

