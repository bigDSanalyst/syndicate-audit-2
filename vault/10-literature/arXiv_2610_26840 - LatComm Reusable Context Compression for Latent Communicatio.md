---
aliases: ["LatComm: Reusable Context Compression for Latent Communication between Large Language Models"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.26840"
url: "http://arxiv.org/abs/2610.26840v1"
published: "2026-10-19T17:58:41Z"
ingested: "2026-10-20T10:54:56Z"
authors:
  - "Huawei Lin"
  - "Jinting Liu"
  - "Tan Yu"
  - "Weijie Zhao"
---

# LatComm: Reusable Context Compression for Latent Communication between Large Language Models

## Abstract

> Systems that combine several large language models (LLMs) often use one context for many
> questions. When the context is passed between models as text, the receiving model processes all
> of its tokens again for every question. Avoiding this cost requires a context representation
> that is compact, reusable across questions, and readable by a different LLM. Existing
> compression and latent communication methods each provide only some of these properties. We
> introduce LatComm, a Latent Communication interface that provides all three by separating
> encoding from reading: the context is encoded once without the question, and the receiver
> selects what to read for each question. A frozen context encoder LLM compresses the context into
> a fixed-size packet and sends it to a different frozen receiver LLM, which reads the packet
> through cross-attention, with gates computed from its prompt. On 12 multiple-choice question-
> answering datasets, LatComm improves average accuracy over single-vector baselines by up to 10.2
> points. On QuALITY, it reduces the receiver's input by 57x and answers the questions of an
> article 3x faster.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

