---
aliases: ["GenOlympiad: Benchmarking Frontier Image Models at Their Capability Boundaries"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.26850"
url: "http://arxiv.org/abs/2610.26850v1"
published: "2026-10-19T17:59:41Z"
ingested: "2026-10-20T10:54:56Z"
authors:
  - "Xi Hu"
  - "Martin Bell"
  - "Liang Zheng"
---

# GenOlympiad: Benchmarking Frontier Image Models at Their Capability Boundaries

## Abstract

> Text-to-image models have made tremendous progress and can produce high-quality images. However,
> a question which would be asked in any other discipline is where the frontier models fall short.
> We introduce GenOlympiad, a benchmark which provides the most challenging text prompts from nine
> capability axes for stress-testing frontier text-to-image models. The assessed capabilities
> include generating large quantities, performing deep reasoning, ensuring hard physical
> consistency, following complex rules and so on. The prompts are designed such that prompt
> alignment is visually verifiable (e.g., counting) instead of relying on subjectiveness (e.g.,
> style). Based on this, we develop an automated evaluation framework which decomposes the prompt
> into easy and hard questions, and for most hard questions, draws help lines to ground evidence
> for accurate grading. We evaluate 20+ strong text-to-image models, including Nano Banana Pro,
> GPT-Image-2.5, Seedream-5.0 and so on. We report that even the best-performing T2I model (Nano
> Banana Pro) only achieves a strict score of 23.9 out of 100 and that coding models such as GPT-6
> Astra have higher prompt alignment scores (but not as visually pleasing). We also derive
> insights in model evolution, alignment with Elo scores, and effectiveness of our grounding-based
> evaluation protocol. Code is available at https://github.com/GenOlympiad/GenOlympiad and the
> project page is at https://genolympiad.github.io/

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

