---
aliases: ["Value as Memory: Online Value-Guided Post-training for General Robot Policies"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.22368"
url: "http://arxiv.org/abs/2610.22368v1"
published: "2026-10-15T17:59:31Z"
ingested: "2026-10-16T10:40:12Z"
authors:
  - "Wenye Yu"
  - "Yijin Chen"
  - "Kaiyi Xiong"
  - "Wenbo Han"
  - "Wendi Chen"
  - "Yang Jin"
  - "Han Xue"
  - "Jun Lv"
  - "Cewu Lu"
  - "Chuan Wen"
---

# Value as Memory: Online Value-Guided Post-training for General Robot Policies

## Abstract

> Real-world post-training of generalist robot policies faces two challenges: partial
> observability makes action selection ambiguous, while offline post-training methods delay
> feedback from deployment experience. We present Value as Memory (VaM), a framework that
> addresses these challenges through value caching and online real-world reinforcement learning
> (RL). Value caching conditions actions on recent value predictions as task-progress memory,
> while online updates enable timely policy improvement by combining offline demonstrations, off-
> policy interventions, and on-policy rollouts for sample-efficient adaptation. As a result, VaM
> transitions from offline RL warmup to online autonomous learning with sparse rewards. Across
> long-horizon tasks involving deformable objects and contact-rich manipulation, VaM yields a mean
> absolute success-rate gain of $29.4\%$ with value caching, while achieving a $32.8\%$ gain with
> online autonomous learning over matched offline training. The evaluated online schedule performs
> $8\times$ as many policy iterations under the same gradient-step budget, with more than
> $2\times$ lower recorded time per gradient step with concurrent data collection and training.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

