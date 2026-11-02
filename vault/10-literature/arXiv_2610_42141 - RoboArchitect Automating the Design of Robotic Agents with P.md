---
aliases: ["RoboArchitect: Automating the Design of Robotic Agents with Persistent Memory"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.42141"
url: "http://arxiv.org/abs/2610.42141v1"
published: "2026-10-30T17:58:48Z"
ingested: "2026-11-02T14:43:38Z"
authors:
  - "Shengguang Wu"
  - "Suning Huang"
  - "Cherie Ho"
  - "Ria Doshi"
  - "Hao Zhu"
  - "Serena Yeung-Levy"
---

# RoboArchitect: Automating the Design of Robotic Agents with Persistent Memory

## Abstract

> Recent work shows that a frozen robot policy performs far better inside an agent harness, where
> control code decides when to query the policy, consult vision tools, or command the arm
> directly. Yet today these harnesses are built by hand and redesigned for each new robot or
> benchmark. We show that harness design can be automated, offering a strong alternative to
> finetuning on a novel setup. In RoboArchitect, a coding model observes a robot's rollouts,
> diagnoses failures, and iteratively revises the harness around the frozen policy. The harness
> evolves on a set of episodes for its optimization and is evaluated on held-out scenes and tasks.
> Without updating any model weights, RoboArchitect raises average success from 9.7% to 43.3% on
> unseen scenes (4.5x) and from 12.7% to 40.2% on unseen tasks (3.2x), across multiple benchmarks
> and policies. The gains are largest where the benchmark is far from the policy's training data:
> wrapping a general-purpose policy, the evolved harness yields a specialist that often
> outperforms even the finetuned version. Intuitive control strategies are automatically designed,
> such as lifting a jammed arm clear or reaching in horizontally when an obstacle blocks the way
> from above. The harness also evolves its own persistent memory, carrying learned experience,
> such as effective grasp depths, into later decisions. These results suggest that substantial
> headroom in robotic manipulation lies in the agent harness, and its design can be effectively
> automated and optimized without weight updates.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

