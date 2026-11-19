---
aliases: ["Jailbreak Detection on Large Language Models via Contrastive Prototype Structures"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.24936"
url: "http://arxiv.org/abs/2611.24936v1"
published: "2026-11-18T18:56:12Z"
ingested: "2026-11-19T15:13:40Z"
authors:
  - "Yan Qiu"
  - "Yuanyuan Li"
---

# Jailbreak Detection on Large Language Models via Contrastive Prototype Structures

## Abstract

> Jailbreak attempts and harmful prompts remain a challenge for the safe deployment of large
> language models. We study whether contrastively learned representations can support safety
> detection without training an additional downstream classifier. We propose Jailbreak Detection
> with Prototype Inference (JDPI), which uses binary safety labels to construct harmful and benign
> prototypes and makes predictions from relative prototype distances. JDPI uses only binary safety
> labels for encoder adaptation, prototype construction, and validation. In our setup, it uses
> fewer labeled examples than the classifier baseline (Method A) by avoiding the separate split
> used to train the downstream classifier. Across four benchmarks covering different input
> formats, contrastive fine-tuning improves JDPI's detection accuracy by 9.1-18.0 percentage
> points. Using the same encoder, JDPI achieves slightly higher ROC-AUC on one benchmark and stays
> within 0.017 of the baseline across all four. With dataset-specific adaptation, JDPI exceeds the
> released Llama Guard 3-8B baseline by 0.173-0.310 in ROC-AUC across the four benchmarks. In
> multi-turn replay on TomGibbs, JDPI uses accumulated user history as the conversation unfolds,
> achieving higher conversation-level accuracy than when it uses the current turn alone. Across 12
> directed transfers, JDPI outperforms the classifier by an average of 1.59 percentage points in
> accuracy, demonstrating stronger cross-dataset robustness.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

