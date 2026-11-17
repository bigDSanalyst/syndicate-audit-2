---
aliases: ["ViRA: Toward Ultra-High-Resolution Visual Agents via Cross-Input Relative Policy Optimization"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.21605"
url: "http://arxiv.org/abs/2611.21605v1"
published: "2026-11-16T18:59:04Z"
ingested: "2026-11-17T15:28:29Z"
authors:
  - "Huawei Lin"
  - "Jinting Liu"
  - "Tongyan Wang"
  - "Xuyang Chen"
  - "Ruihua Shi"
  - "Zhichao Xu"
  - "Jiaxin Qin"
  - "Guoshenghui Zhao"
  - "Baijian Yang"
  - "Yingjie Victor Chen"
  - "Tan Yu"
  - "Weijie Zhao"
---

# ViRA: Toward Ultra-High-Resolution Visual Agents via Cross-Input Relative Policy Optimization

## Abstract

> Visual agents answer questions about ultra-high-resolution photos by zooming into the relevant
> regions. However, existing agents often answer from common sense instead of reading the
> evidence. Reinforcement learning (RL) on the final answer cannot correct this, because a guess
> earns the same reward as reading. We propose Cross-Input Relative Policy Optimization
> (CrossRPO), which trains agents on contrast sets. A contrast set asks one question about several
> versions of an image that differ only in a small region with the evidence and have different
> answers, so only reading the evidence solves the whole set. CrossRPO rewards solving the whole
> set, and we prove that it does not reinforce a set answered from common sense. We build contrast
> sets for training (ViRA-Train) and evaluation (ViRA-Bench) by editing one small object in images
> of 21 to 120 megapixels, and we photograph further sets with real changes (ViRA-Bench-Real) to
> exclude editing traces. We train two Visual Reasoning Agents, ViRA-9B and ViRA-27B, with
> CrossRPO on only about 3,500 items of ViRA-Train each. CrossRPO achieves 63.3% set accuracy on
> ViRA-Bench at the maximum resolution, against 59.3% for GRPO. ViRA-9B is the most accurate open
> model of its size on all benchmarks, and ViRA-27B outperforms Claude Haiku 5.5 and GPT-6-Luna,
> both at their highest thinking level, on most benchmarks.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

