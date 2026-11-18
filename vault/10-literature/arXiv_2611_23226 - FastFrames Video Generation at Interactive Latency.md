---
aliases: ["FastFrames: Video Generation at Interactive Latency"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.23226"
url: "http://arxiv.org/abs/2611.23226v1"
published: "2026-11-17T18:59:13Z"
ingested: "2026-11-18T15:04:09Z"
authors:
  - "Gene Chou"
  - "Guandao Yang"
  - "Fujun Luan"
  - "Lars Mescheder"
  - "Wei Dong"
  - "Stephan Richter"
  - "Vladlen Koltun"
---

# FastFrames: Video Generation at Interactive Latency

## Abstract

> Autoregressive video diffusion models generate frames based on new observations and inputs,
> making them a promising medium for interactive visual experiences. However, existing models are
> orders of magnitude too slow for fluid interaction. This paper introduces FastFrames, a family
> of fast autoregressive video diffusion models that achieves interactive latency without
> compromising quality. We profile the inference pipeline of state-of-the-art models and find that
> operations often treated as fixed implementation details, such as VAE decoding and KV cache
> updates, in fact account for over half of end-to-end inference latency. We challenge the
> assumption that these components are indispensable and replace them with lightweight
> alternatives. Our 1.3B variant runs at 36 ms per frame, or 28 responses per second (RPS), on a
> single B200 GPU while matching the generation quality of a state-of-the-art model that is nearly
> 8x slower. Our 14B variant runs at 45 ms per frame, or 22 RPS, on an 8x B200 GPU node and yields
> significantly better visual quality and realism. We show that FastFrames enables real-time
> interaction in applications such as camera-conditioned and physics-conditioned video generation.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

