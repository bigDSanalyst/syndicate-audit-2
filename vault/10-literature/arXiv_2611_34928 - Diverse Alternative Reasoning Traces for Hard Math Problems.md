---
aliases: ["Diverse Alternative Reasoning Traces for Hard Math Problems"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.34928"
url: "http://arxiv.org/abs/2611.34928v1"
published: "2026-11-25T18:59:11Z"
ingested: "2026-11-26T16:21:38Z"
authors:
  - "Lukas Aichberger"
  - "Adam Golinski"
  - "Arno Blaas"
  - "Arwen Bradley"
  - "Jacob Springer"
  - "Mehrdad Farajtabar"
  - "Michael Kirchhof"
  - "Sinead Williamson"
---

# Diverse Alternative Reasoning Traces for Hard Math Problems

## Abstract

> Post-training large language models (LLMs) for mathematical reasoning often relies on accepted
> traces whose final answers pass a verifier. For hard math problems, however, such traces can be
> rare under independent Monte Carlo (MC) sampling. To address this, we propose Diverse
> Alternative Reasoning Traces (DART), a trace-mining method that starts from a rejected trace,
> decomposes it into reasoning steps, and ranks them by position-weighted uncertainty. It then
> generates deliberately distinct alternative candidates for highly ranked steps using reference-
> answer guidance and a meta-thought before completing the resulting traces. On greedy-unsolved
> DeepMath-103K problems, DART recovers 37% more problems than MC sampling at a matched number of
> generated traces. Its estimated generation cost per recovered problem is nearly identical, while
> its cost per accepted trace is 30% lower. Post-training Llama-3.1-8B-Instruct on traces mined by
> DART achieves the highest point estimate in five of six evaluations across MATH-500 and AIME
> benchmarks. These results demonstrate that revisiting rejected traces with DART can expand
> problem coverage and provide effective post-training data.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

