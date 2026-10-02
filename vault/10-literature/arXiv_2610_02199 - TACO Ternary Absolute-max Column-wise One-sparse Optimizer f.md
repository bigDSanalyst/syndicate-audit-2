---
aliases: ["TACO: Ternary Absolute-max Column-wise One-sparse Optimizer for LLM Fine-Tuning"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.02199"
url: "http://arxiv.org/abs/2610.02199v1"
published: "2026-10-01T17:59:42Z"
ingested: "2026-10-02T11:51:31Z"
authors:
  - "Jichao Jiang"
  - "Cristian McGee"
  - "El Houcine Bergou"
  - "Hanqin Cai"
  - "Aritra Dutta"
---

# TACO: Ternary Absolute-max Column-wise One-sparse Optimizer for LLM Fine-Tuning

## Abstract

> Full-parameter fine-tuning of large language models (LLMs) incurs substantial optimizer state
> memory overhead, limiting the model sizes that fit on modern GPUs. Existing approaches either
> compress optimizer state, abandon first-order gradients, or change the update geometry while
> retaining dense state. The recently introduced Muon optimizer reduces optimizer memory through
> matrix-valued updates. Still, its geometry differs from AdamW and can lead to performance
> degradation when fine-tuning AdamW-pretrained models. To reduce optimizer memory without
> sacrificing accuracy or computational efficiency in LLM fine-tuning, we propose Ternary
> Absolute-max Column-wise One-sparse optimizer, or TACO, which follows Muon's operator-norm
> steepest-descent view but takes the geometric route further. TACO computes the exact steepest-
> descent direction under a dimension-normalized $1\to1$ operator norm by selecting the sign of
> the largest magnitude entry in each column of two-dimensional weight matrices. This retains
> first-order gradients while making optimizer state memory nearly negligible. Our practical TACO
> optimizer maintains only a small set of low precision gradient components per column, reducing
> persistent optimizer state by $174\times$ relative to AdamW8bit (from 27.7 GB to 0.16 GB) and
> peak training memory by $2.9\times$ (from 80.6 GB to 27.5 GB) on OPT-13B, while achieving
> comparable accuracy and runtime. TACO further enables full-parameter fine-tuning of
> 30-32B-parameter models on a single 80 GB H100 GPU across multiple model families and tasks.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

