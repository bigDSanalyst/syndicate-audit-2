---
aliases: ["Weight Placement Is Not Enough: Synchronization in Multi-Node CPU Decoding of Ternary LLMs"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.28620"
url: "http://arxiv.org/abs/2610.28620v1"
published: "2026-10-20T17:56:35Z"
ingested: "2026-10-21T11:08:15Z"
authors:
  - "Runguo Li"
  - "Dezhen Lu"
---

# Weight Placement Is Not Enough: Synchronization in Multi-Node CPU Decoding of Ternary LLMs

## Abstract

> Ternary LLMs read only a few gigabytes per decoded token, yet on dual-socket servers with four
> NUMA nodes the fastest ternary runtime we found uses less than half of the memory bandwidth.
> Placing each weight on the node of the thread that reads it is necessary but not enough: in a
> decode engine with node-local weights that reuses ik_llama.cpp's kernels, threads on two
> generations of Xeon servers still spend 20-48% of each token waiting at synchronization points.
> Per-thread barrier traces show that most of the wait is for the slowest threads of each node;
> the barriers' own latency (microseconds each, but up to 12% of the token for the smallest model)
> and serial per-node work are smaller parts. On identical kernels, a Megatron-style column split
> beats a row-owned split without cross-node reductions in every configuration we measured, and
> isolating the number of barriers shows that most of its gain comes from its threads waiting less
> for each other and for their node leaders, and only a minority from having fewer barriers. Where
> decoding is DRAM-bound, the resulting engine is 1.5-2.1x faster than ik_llama.cpp with all cores
> and 1.5-1.9x faster than ik_llama.cpp at its fastest thread count (3.2x and 2.8x for a small
> model that runs from the L3 cache), at the same accuracy and with less energy per token.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

