---
aliases: ["Rephrase Before You Act: Characterizing and Mitigating Language Sensitivity in Vision-Language-Action Models"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.10526"
url: "http://arxiv.org/abs/2610.10526v1"
published: "2026-10-07T17:57:38Z"
ingested: "2026-10-08T12:47:26Z"
authors:
  - "Mikey Watts"
  - "Yuchen Cui"
---

# Rephrase Before You Act: Characterizing and Mitigating Language Sensitivity in Vision-Language-Action Models

## Abstract

> Vision-language-action models (VLAs) are strikingly sensitive to instruction phrasing and do not
> inherit the language robustness of the vision-language models they are built on. A one-word edit
> can move success by tens of points: $π_{0.5}$ turns on a LIBERO stove 100% of the time for
> "switch on the stove" and 2% for "switch on the hot plate", and a $π_0$ checkpoint finetuned
> with rephrase augmentation still shows swings of up to 61 points. We characterize this
> sensitivity with statistically tested single-edit swings and an oracle phrase search, which
> shows that phrasing alone nearly closes the 21-point gap between in-distribution and out-of-
> distribution tasks. We then reduce it without modifying the policy. Because the sensitivity is
> systematic, it can be expressed as explicit rules: we score many phrasings of a few training
> tasks, have a large language model distill the evidence into ten to twenty rephrasing rules, and
> at deployment rewrite each incoming instruction once under these rules. The rules improve the
> frozen $π_0$ by 16 to 27% relative on twelve held-out tasks across adversarial, VLM-generated,
> and human-generated phrasings, with gains concentrated on out-of-distribution tasks. The
> pipeline replicates on $π_{0.5}$ and LIBERO, lifting in-finetune success from 93.6% to 97.8%.
> The method requires no retraining and no per-step verification, and applies zero-shot to unseen
> tasks and instructions. Project website: https://sttawm.github.io/rephrase-before-you-act

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

