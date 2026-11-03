---
aliases: ["PDFP: GPU-Accelerated Feasibility Pump via PDHG"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.03629"
url: "http://arxiv.org/abs/2611.03629v1"
published: "2026-11-02T18:54:16Z"
ingested: "2026-11-03T13:36:38Z"
authors:
  - "Ruofeng Liu"
  - "Haihao Lu"
  - "Rahul Mazumder"
---

# PDFP: GPU-Accelerated Feasibility Pump via PDHG

## Abstract

> The feasibility pump (FP) is among the most widely used primal heuristics for mixed-integer
> linear programming. It alternates between rounding an LP-feasible point and projecting the
> rounded point back onto the feasible region of the LP relaxation. Recent pump-based heuristics
> compute the projection with the primal--dual hybrid gradient method (PDHG), which is scalable on
> modern GPUs. They pose it as a linear program, which needs auxiliary variables and constraints
> for general integers. Once the projection runs on the GPU, the constraint-propagation rounding
> (CPR) of FP~2.0 takes a large share of each iteration. For the projection, we propose PDFP, a
> custom first-order method that solves the pump's projection problem directly, without auxiliary
> primal variables or constraints. We prove that it keeps the accelerated linear rate of restarted
> Halpern PDHG. For the rounding, we propose a new procedure that is more efficient than CPR and,
> under certain assumptions, still returns a CPR rounding. It also chooses rounded values by
> constraint violation, which can produce feasible roundings where nearest rounding cannot.
> Finally, our pump runs two independent trajectories concurrently on one GPU through CPU--GPU
> synchronization. This exploits the variance in trajectory length and lets the pump terminate
> sooner on average. Computational experiments on MIPLIB~2017 instances show early, promising
> results: these contributions speed up the discovery of the first incumbent solution. The code is
> publicly available at https://github.com/MIT-Lu-Lab/PDFP.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

