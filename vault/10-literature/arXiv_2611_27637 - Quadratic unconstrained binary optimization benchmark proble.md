---
aliases: ["Quadratic unconstrained binary optimization benchmark problems from mixed Hamming packings"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.27637"
url: "http://arxiv.org/abs/2611.27637v1"
published: "2026-11-20T14:00:45Z"
ingested: "2026-11-23T17:21:01Z"
authors:
  - "Péter Naszvadi"
  - "Marcell Tukora"
  - "Roman Kužel"
  - "Mátyás Koniorczyk"
---

# Quadratic unconstrained binary optimization benchmark problems from mixed Hamming packings

## Abstract

> Benchmarking exact solvers and noisy intermediate-scale quantum devices for quadratic
> unconstrained binary optimization (QUBO) requires small yet challenging instances, preferably
> coming from actual applications. We propose such a benchmark set derived from mixed Hamming
> packing, a hard problem in coding theory. Starting from its mixed-integer linear programming
> formulation, we provide a generator for the equivalent QUBO models and study 133 instances whose
> optima are certified by that formulation. In the feature space of the MQLib library, we position
> a broad range of existing quantum-oriented benchmarks relative to the classical ones: they lie
> along a narrow, sparse border of the region covered by MQLib, whereas our instances form a
> coherent family in a region that both collections leave almost empty. Classical heuristics and a
> simulated bifurcation machine find the optimum of most instances quickly, in several cases
> sooner than an exact mixed-integer solver first encounters it, suggesting heuristic warm starts
> for exact solvers; for an exact QUBO solver, in turn, it appears challenging to prove
> optimality. In Ising form, the instances are densely connected antiferromagnets whose large
> local fields are almost exactly balanced by the couplings, so that the decision on each variable
> rests on a small remainder. This makes them hard to embed and to represent accurately on current
> quantum annealers, in line with our D-Wave experiments.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

