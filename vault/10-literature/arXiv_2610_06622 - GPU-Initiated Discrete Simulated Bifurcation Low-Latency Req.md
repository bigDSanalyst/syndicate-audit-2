---
aliases: ["GPU-Initiated Discrete Simulated Bifurcation: Low-Latency Requests and Streaming Dense Couplings"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.06622"
url: "http://arxiv.org/abs/2610.06622v1"
published: "2026-10-05T16:20:06Z"
ingested: "2026-10-06T12:43:37Z"
authors:
  - "Yaocheng Chen"
---

# GPU-Initiated Discrete Simulated Bifurcation: Low-Latency Requests and Streaming Dense Couplings

## Abstract

> GPU-based optimization faces two communication bottlenecks: coordinating frequent requests and
> delivering dense models that exceed device memory. We present a discrete simulated bifurcation
> (dSB) architecture that addresses both through NVIDIA DOCA GPUNetIO. For resident models, a
> persistent service receives field updates, executes each solve within one GPU thread block, and
> returns the result. Exact integer coupling sums, GPU work queues, and batched transmission keep
> the receive--solve--reply path on the device without a dedicated CPU data-path core. In
> comparisons with socket-based servers using the same solver, the largest latency gains occur
> under concurrent load. As the offered load increases from 400 to 800 thousand requests per
> second, median round-trip latency rises by only 6\%. At the highest tested load, median and
> 99th-percentile latencies are 189 and 218~$μ$s, compared with 288 and 609~$μ$s for the tuned
> persistent CPU proxy across repeated runs. For models larger than device memory, a streaming
> solver retains dynamical state on the GPU and reuses incoming coupling tiles across replicas. It
> evaluates ten-million-variable dense binary matrices at approximately 307~Gb/s, consuming a
> 12.5-TB logical matrix through a 64-MiB packet buffer. Ground-state recovery on planted
> instances and agreement with reference executions verify the computation. Together, the two
> modes scale dSB to concurrent requests and dense models beyond GPU memory.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

