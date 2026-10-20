---
aliases: ["Quantum algorithms for optimal control: large-scale finite-horizon linear-quadratic regulation"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.26843"
url: "http://arxiv.org/abs/2610.26843v1"
published: "2026-10-19T17:58:57Z"
ingested: "2026-10-20T10:54:56Z"
authors:
  - "Xiajie Huang"
  - "Cristina Álvarez Yuste"
  - "Nikita Guseynov"
  - "Nana Liu"
  - "Javier González-Conde"
---

# Quantum algorithms for optimal control: large-scale finite-horizon linear-quadratic regulation

## Abstract

> We develop quantum algorithms for optimal control over a prescribed finite time interval (finite
> horizon), focusing on continuous-time linear-quadratic regulation (LQR). This foundational
> control problem often requires solving a nonlinear matrix Riccati equation, which can be costly
> for large systems and long control durations on conventional classical solvers. We instead work
> directly with the state-costate optimality equations, reformulating the LQR problem as a
> multiple-shooting linear system. Importantly, we prove a condition-number bound for the system
> that is independent of the horizon, under stabilizability and detectability assumptions. By
> incorporating the initial and final conditions into a single linear system, we can solve the
> subsequent linear system more efficiently with a quantum linear systems subroutine. For a given
> initial state, our quantum algorithms return classical estimates of the optimal cost and the
> optimal control inputs at a selected time, without constructing a Riccati solution operator.
> Given sparse-matrix block-encodings, an initial-state preparation oracle and a fixed number of
> control inputs, the query and gate complexities scale polylogarithmically with system size and
> control duration, provided that sparsity, relevant norms, and stability parameters are bounded.
> The dependence on the target error is inverse-linear up to logarithmic factors. We establish the
> required bounds uniformly in system size and duration for a family of damped mass-spring chains
> with two endpoint controls. Numerical experiments support the analysis.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

