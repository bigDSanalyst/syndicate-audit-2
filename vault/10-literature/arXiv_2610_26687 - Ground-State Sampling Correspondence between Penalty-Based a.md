---
aliases: ["Ground-State Sampling Correspondence between Penalty-Based and Constrained Quantum Annealing"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.26687"
url: "http://arxiv.org/abs/2610.26687v1"
published: "2026-10-19T16:32:59Z"
ingested: "2026-10-20T10:54:52Z"
authors:
  - "Shunta Ide"
  - "Shu Tanaka"
---

# Ground-State Sampling Correspondence between Penalty-Based and Constrained Quantum Annealing

## Abstract

> Quantum annealing generally samples degenerate ground states with nonuniform probabilities. This
> unfair sampling depends on how the driver Hamiltonian couples these states near the end of
> annealing. For combinatorial optimization problems with a cardinality constraint, the penalty
> method and constrained quantum annealing (CQA) differ in these couplings. The transverse-field
> driver of the penalty method does not directly couple feasible ground states, whereas the fully
> connected XY driver of CQA couples pairs of them related by a single spin exchange. We
> investigate how this difference affects ground-state sampling, using closed-system simulations
> of random graph bipartitioning instances together with degenerate perturbation theory. For the
> instances studied, the conditional ground-state distribution of penalty-based quantum annealing
> approaches that of CQA at sufficiently large penalties and long annealing times. This
> convergence can be explained by the effective Hamiltonian of penalty-based quantum annealing, in
> which virtual single-spin flips to infeasible states generate a second-order interaction
> proportional to the CQA driver projected onto the feasible ground-state manifold, which is the
> leading term of the effective Hamiltonian of CQA. In the numerical simulations, the Jensen--
> Shannon divergence between the conditional ground-state distributions of penalty-based quantum
> annealing and CQA decreases approximately as the inverse square of the penalty-to-objective
> energy ratio, consistent with the perturbative analysis. This correspondence between the
> effective Hamiltonians extends to equal-weight fixed-magnetization constraints under the same
> perturbative conditions, providing a common mechanism for sampling bias in the two
> implementations.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

