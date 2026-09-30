---
aliases: ["LeapQuant: Efficient Linear Attention with Accurate Recurrent State Quantization"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.38166"
url: "http://arxiv.org/abs/2609.38166v1"
published: "2026-09-29T17:59:34Z"
ingested: "2026-09-30T11:54:08Z"
authors:
  - "Yi Pan"
  - "Haocheng Xi"
  - "Kan Zhu"
  - "Xingyang Li"
  - "Yibo Wu"
  - "Mayank Mishra"
  - "Hongtao Zhang"
  - "William X. Zheng"
  - "Baris Kasikci"
  - "Song Han"
  - "Kurt Keutzer"
  - "Rishabh Iyer"
  - "Ion Stoica"
---

# LeapQuant: Efficient Linear Attention with Accurate Recurrent State Quantization

## Abstract

> Recent LLMs increasingly adopt hybrid designs that replace standard attention with linear
> attention, such as Gated DeltaNet (GDN) and Kimi Delta Attention (KDA). Although they compress
> the context into a fixed-size recurrent state and substantially reduce the cost of long-context
> processing, repeatedly reading and updating that state remains a major inference bottleneck.
> Quantization offers a natural way to reduce this cost, but can significantly degrade model
> quality, due to the accumulation of rounding errors and the presence of outlier rows and columns
> in the state. To address these challenges, we propose LeapQuant, a training-free method that
> achieves near-lossless performance under 8-bit recurrent-state quantization. First, to mitigate
> error accumulation, we propose per-window quantization, which leaps over a window of tokens and
> quantizes the state only once at its end. Within a window, outputs are computed from the fixed
> low-bit state together with high-precision buffered updates. Second, to reduce the error
> introduced by each quantization, LeapQuant retains the state's largest outliers as a few high-
> precision Compensator Tokens, which share the update path of real tokens. We then smooth the
> remaining residual before quantization to further reduce the error. Comprehensive experiments
> across the Qwen, Kimi, and GLM model families show that LeapQuant substantially reduces memory
> and compute costs during inference. With accuracy comparable to the FP32 baseline, it achieves
> average speedups of 2.05--3.70$\times$ at the kernel level and 1.47$\times$ for end-to-end
> inference on NVIDIA B200, RTX PRO 6000, and RTX 5090 GPUs.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

