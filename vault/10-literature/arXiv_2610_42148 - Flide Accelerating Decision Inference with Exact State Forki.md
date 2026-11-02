---
aliases: ["Flide: Accelerating Decision Inference with Exact State Forking"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.42148"
url: "http://arxiv.org/abs/2610.42148v1"
published: "2026-10-30T17:59:38Z"
ingested: "2026-11-02T14:43:38Z"
authors:
  - "Bobo Li"
  - "Jiajia Song"
  - "Hao Fei"
  - "Wynne Hsu"
  - "Mong Li Lee"
---

# Flide: Accelerating Decision Inference with Exact State Forking

## Abstract

> Decision models such as Jev have emerged as a highly promising paradigm for LLM agent systems,
> providing lightweight and reliable categorical reasoning for rapid System One execution.
> However, existing generation-oriented inference engines fail to support these workloads
> effectively, suffering from severe prefix recomputation overheads or distorted output
> probabilities. To address this challenge, we propose Flide, an efficient and exact inference
> engine that decouples the logical tree structure of a decision request from its physical
> execution within a single flattened token stream. Through ForkAttention, Flide navigates request
> dependencies using GPU-resident indices across both standard attention and recurrent Gated
> DeltaNet layers, guaranteeing in exact arithmetic that every query branch evaluates identically
> to an isolated forward pass. By expressing branch topologies directly in GPU-resident metadata,
> Flide accommodates diverse request mixtures with a compact set of pre-recorded execution graphs
> while enabling expanding agent histories to resume from checkpoints saved in earlier passes.
> Extensive evaluations on public hybrid and decision models demonstrate that Flide answers
> queries up to 9.5 times faster than vLLM and SGLang while staying closest to a float32 reference
> in total variation distance. By unifying physical execution throughput with mathematical
> exactness, Flide establishes a principled foundation for scalable, latency-critical decision
> intelligence in agent systems.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

