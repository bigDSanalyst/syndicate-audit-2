---
aliases: ["How to Build Pseudorandom Unitaries in Microcrypt"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.03711"
url: "http://arxiv.org/abs/2610.03711v1"
published: "2026-10-02T17:58:06Z"
ingested: "2026-10-05T13:34:05Z"
authors:
  - "Aditya Gulati"
  - "Dakshita Khurana"
  - "Kabir Tomer"
---

# How to Build Pseudorandom Unitaries in Microcrypt

## Abstract

> We provide the first evidence relative to a classical oracle that pseudorandom unitaries (PRUs)
> can exist without quantum-computable one-way functions. To obtain this result, we first prove
> that five independent random diagonal phase layers interleaved with Hadamard transforms \[
> U=F_5HF_4HF_3HF_2HF_1 \] form a strong PRU with security under adaptive, controlled access to
> the unitary, its inverse, transpose, and complex conjugate. Our main result is that, when the
> phase layers are implemented using a classical random oracle O, the construction remains secure
> against uniform BQP adversaries with coherent access to suitable Boolean completions of
> classical-input $QMA^{PH}^{O}}$ decision problems. Such an adversary can invert (even quantum-
> computable) one-way functions and solve efficiently verifiable one-way puzzles defined relative
> to O. Our result therefore provides classical-oracle evidence that PRUs do not imply quantum-
> computable one-way functions, in the form of a black-box separation. We substantially strengthen
> the classical-oracle result of Kretschmer, Qian, and Tal (STOC 2025) by obtaining PRUs secure
> against these QMA-aided adversaries. Our construction also consists of a simple, efficient
> circuit that queries a random function, suggesting a route to concrete implementation via the
> random-oracle heuristic.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

