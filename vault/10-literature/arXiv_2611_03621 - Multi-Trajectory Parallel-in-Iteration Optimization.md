---
aliases: ["Multi-Trajectory Parallel-in-Iteration Optimization"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.03621"
url: "http://arxiv.org/abs/2611.03621v1"
published: "2026-11-02T18:51:46Z"
ingested: "2026-11-03T13:36:38Z"
authors:
  - "Guilherme H. M. Araujo"
  - "Oliver A. Krzysik"
  - "Hans De Sterck"
---

# Multi-Trajectory Parallel-in-Iteration Optimization

## Abstract

> Previously, we developed a ``parallel-in-iteration'' optimization framework that uses multigrid
> reduction-in-time (MGRIT) to parallelize slowly converging optimization methods, such as
> gradient descent. Unlike time-dependent evolution problems, optimization requires only a final
> point with a sufficiently small gradient, rather than an accurate approximation of the entire
> trajectory of iterates. This motivates a different use of MGRIT: instead of repeatedly improving
> the approximation of a single long trajectory, we introduce restarted MGRIT (R-MGRIT), which
> performs one MGRIT iteration on a trajectory, takes the approximate final point as a new initial
> guess, and repeats the process on a new trajectory. Each restart thus defines a new all-at-once
> system, allowing progress toward the solution without accurately approximating the preceding
> trajectory. Moreover, we find that these trajectories can be shortened without increasing the
> number of restarts needed for convergence. We provide theoretical results comparing MGRIT and
> R-MGRIT for linear problems and demonstrate the convergence behavior of the shortened
> trajectories numerically for both linear and nonlinear problems. Shortening the trajectories
> increases the estimated parallel speedup while reducing the number of processors required.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

