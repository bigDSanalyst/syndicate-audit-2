---
aliases: ["Speculative Forcing for Efficient Autoregressive Video Generation"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.22347"
url: "http://arxiv.org/abs/2610.22347v1"
published: "2026-10-15T17:57:01Z"
ingested: "2026-10-16T10:40:12Z"
authors:
  - "Hyunwook Choi"
  - "Seungryong Kim"
  - "Dongyoon Han"
  - "Sangdoo Yun"
---

# Speculative Forcing for Efficient Autoregressive Video Generation

## Abstract

> Few-step autoregressive video generators enable streaming generation, yet they run every token
> through the final denoising step, regardless of how much refinement it needs. We find this
> uniform computation is often unnecessary: many tokens already closely match their eventual full-
> step outputs in the initial steps, while others require refinement until the end. We introduce
> Speculative Forcing, a framework that treats intermediate clean estimates as drafts and predicts
> when individual tokens can be safely accepted early. Once accepted, a token is frozen as its
> final output and undergoes no further denoising, while its cached keys and values remain
> available as context for the remaining tokens. We explore two alternative verifier designs: a
> training-free one based on similarity to clean content and stability across steps, and a learned
> one that reads the frozen generator's intermediate features to estimate each token's remaining
> gap to its full-step output. Across short-video, long-video, and world generation, Speculative
> Forcing preserves the quality of full-step sampling while substantially reducing computation. On
> LongLive, it matches the four-step generator with ~1.7 denoising steps per token, running over
> 1.5x faster at 41.7 and 37.8 fps. On Lingbot-World 2.0, where camera motion continually changes
> the visible content, it maintains quality with ~2.5 denoising steps per token and runs 1.35x
> faster at 24.5 fps.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

