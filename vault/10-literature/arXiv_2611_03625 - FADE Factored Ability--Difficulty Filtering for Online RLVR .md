---
aliases: ["FADE: Factored Ability--Difficulty Filtering for Online RLVR Scheduling"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.03625"
url: "http://arxiv.org/abs/2611.03625v1"
published: "2026-11-02T18:53:23Z"
ingested: "2026-11-03T13:36:38Z"
authors:
  - "Tomas Duncun"
  - "Jonah Ellison"
  - "Mateo Ruiz"
  - "Hanae Fujita"
  - "Ingrid Solberg"
---

# FADE: Factored Ability--Difficulty Filtering for Online RLVR Scheduling

## Abstract

> Group-based reinforcement learning with verifiable rewards (RLVR) learns only from prompts whose
> sampled completions disagree: all-pass and all-fail groups produce zero relative advantage and
> burn generation budget without moving the policy. Adaptive schedulers try to steer rollouts
> toward informative prompts, yet they rely on per-prompt pass-rate trackers that entangle two
> quantities evolving at very different speeds---the policy's shifting competence across reasoning
> skills and each prompt's intrinsic difficulty. When a single exponential average or Beta counter
> tracks both at once, short memory scrambles the relative ordering of prompts whereas long memory
> reports stale pass rates. We introduce FADE (Factored Ability--Difficulty Estimation), a
> bilinear state-space filter that separates the two timescales. FADE represents each prompt's
> success logit as the inner product of a whitened $K$-dimensional skill loading with a fast-
> drifting policy ability vector, minus a slow-shrinking scalar item intercept. Using Pólya--Gamma
> augmentation, each minibatch of binary rollout outcomes updates the $K$-dimensional ability
> posterior in closed form via a rank-$K$ Woodbury step, instantly transferring competence shifts
> to all unobserved prompts that share those skills while leaving item intercepts stable. From the
> resulting posterior mean and variance we derive a closed-form utility for the probability of
> drawing a non-degenerate rollout group. Across five reasoning benchmarks, two base models, and
> four scheduling paradigms under a matched rollout budget, FADE consistently improves downstream
> accuracy and calibration while adding less than $0.6$\,ms per step.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

