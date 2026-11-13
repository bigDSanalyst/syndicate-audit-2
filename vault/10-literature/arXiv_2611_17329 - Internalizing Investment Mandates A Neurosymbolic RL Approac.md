---
aliases: ["Internalizing Investment Mandates: A Neurosymbolic RL Approach to Portfolio Allocation"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.17329"
url: "http://arxiv.org/abs/2611.17329v1"
published: "2026-11-12T18:59:37Z"
ingested: "2026-11-13T13:54:15Z"
authors:
  - "Zeynep Yıldız"
  - "Satchit Chatterji"
  - "Ercan Atam"
  - "Erman Acar"
---

# Internalizing Investment Mandates: A Neurosymbolic RL Approach to Portfolio Allocation

## Abstract

> Institutional portfolios operate under investment policy statements that specify asset
> allocation constraints, often conditioned on market regime information. Deep reinforcement
> learning has been shown to optimize financial performance but typically does not enforce rule
> compliance, making it unsuitable for real-world deployment. Existing neurosymbolic methods such
> as Probabilistic Logic Policy Gradient (PLPG) offer constraint-satisfying reinforcement learning
> (RL) via differentiable symbolic supervision but assume a finite, discrete action space. We
> present a PLPG-inspired continuous allocation method that estimates the probability that the
> policy's own executed action satisfies the investment mandate, using reparameterized Monte Carlo
> sampling, and adds it to the training objective. No post-hoc enforcement mechanism intercepts
> actions at inference time and compliance is learned by the agent. Audited directly on
> deterministic mean actions with no correction, the policy reduces violations of a six-rule
> regime-conditional mandate from 96-98% for unconstrained RL and 33.4% for a reward-penalty
> baseline to 4.8%, showing that a continuous-action neurosymbolic policy can substantially
> internalize a symbolic mandate.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

