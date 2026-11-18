---
aliases: ["Spool: Low-Latency Streaming Inference for Hybrid Vision-Language Models"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.23228"
url: "http://arxiv.org/abs/2611.23228v1"
published: "2026-11-17T18:59:27Z"
ingested: "2026-11-18T15:04:09Z"
authors:
  - "Rui Ning"
  - "Om Chabra"
  - "Hari Balakrishnan"
---

# Spool: Low-Latency Streaming Inference for Hybrid Vision-Language Models

## Abstract

> Applications such as visual accessibility agents and robotics require answering questions about
> recent video content promptly, over a bounded window of past frames (e.g., the last two
> minutes). Hybrid vision-language models (VLMs), which interleave attention with linear recurrent
> layers such as Gated DeltaNet (GDN), are attractive for this setting, but maintaining a sliding
> window is expensive. The reason is that recurrent layers combine all past frames into a shared
> state, so expiring old frames normally requires re-running the entire window through the model.
> We observe that the recurrent update is affine in the state with input-dependent coefficients,
> so the effect of each frame can be captured as a transformation that composes associatively. We
> present Spool, a training-free framework that caches per-frame state transformations and
> composes them efficiently as the window advances, removing expired frames from each recurrent
> layer's state without replaying frames through the backbone. Removal is exact within each layer;
> as with key-value eviction in attention, expired frames can retain residual influence through
> the cached inputs computed by earlier layers. We design a dedicated data structure and GPU
> kernels to achieve low caching and composition overhead. Across five open-source hybrid VLMs and
> four video reasoning benchmarks, Spool achieves the lowest p95 time-to-first-token in all 20
> model-benchmark tests, reducing it by a geometric mean of $6.6\times$ over the faster of two
> recent vLLM baselines, while improving accuracy by 2.3 percentage points on average.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

