---
aliases: ["Trust the Direction, Search the Step: Zero-and-First-Order Methods for LLM Fine-Tuning"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.02190"
url: "http://arxiv.org/abs/2610.02190v1"
published: "2026-10-01T17:59:28Z"
ingested: "2026-10-02T11:51:31Z"
authors:
  - "Cristian McGee"
  - "El Houcine Bergou"
  - "Aritra Dutta"
---

# Trust the Direction, Search the Step: Zero-and-First-Order Methods for LLM Fine-Tuning

## Abstract

> Step-size selection remains a central challenge in large-scale neural network optimization;
> conservative steps slow convergence, while aggressive steps can destabilize it. We combine
> \textbf{Z}ero-and-\textbf{F}irst-\textbf{O}rder optimization~(ZFO) and propose a lightweight
> framework that decouples direction selection from step-size. ZFO uses a trusted first-order
> optimizer to determine the direction and performs zeroth-order evaluations only along this one-
> dimensional subspace to choose how far to move. Using the current {gradient information} and two
> additional objective function evaluations, ZFO instances construct a local model of the
> objective function along the proposed direction and select a curvature-aware step within a
> bounded search interval. This yields an adaptive step-selection mechanism that costs less than a
> full line search. We provide theoretical guarantees to show that shared-sample evaluations
> produce reliable finite-difference curvature estimates, that the induced local model selects a
> near-optimal step along the search interval, and that ZFO converges to a neighborhood of a
> stationary point. Across the evaluated settings, language models and datasets, ZFO frequently
> improves optimization and final performance relative to fixed-step first-order baselines, with
> the magnitude and preferred local model depending on the objective. Our code is publicly
> available at: https://github.com/nizswan/Zeroth-First-Order-Framework.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

