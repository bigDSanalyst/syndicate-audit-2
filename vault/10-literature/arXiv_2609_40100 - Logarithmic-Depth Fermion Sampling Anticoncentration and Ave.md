---
aliases: ["Logarithmic-Depth Fermion Sampling: Anticoncentration and Average-Case Hardness"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.40100"
url: "http://arxiv.org/abs/2609.40100v1"
published: "2026-09-30T16:35:44Z"
ingested: "2026-10-01T12:24:51Z"
authors:
  - "Natansh Mathur"
  - "Iordanis Kerenidis"
---

# Logarithmic-Depth Fermion Sampling: Anticoncentration and Average-Case Hardness

## Abstract

> Sampling problems give some of the clearest conditional separations between quantum and
> classical computation. In Fermion Sampling, passive linear optics acts on a non-Gaussian magic
> input. Globally Haar-random transformations give anticoncentration and high-precision average-
> case hardness, but require linear depth and quadratically many gates. A natural open question is
> whether linear depth is necessary? We show that logarithmic depth suffices for both guarantees
> in the same ensemble. For fresh uniform matchings with independent Haar two-mode gates, the
> collision reaches the passive-Haar scale at a sharp threshold of $\log
> n/\log(9/4)\approx0.855\log_2 n$ layers, with an explicit limiting transition profile and a
> matching lower bound from two-particle correlations. The mechanism is input-dependent: the magic
> input suppresses the extensive weight of the slowest relaxation mode, leaving the next to set
> the scale. An occupation-basis input retains large collision even under full Haar randomness. At
> a larger logarithmic depth, we prove, in the real-RAM model, average-case
> $\#\mathsf{P}$-hardness of estimating output probabilities to additive error $2^{-O(n\log^2 n)}$
> on any fixed fraction of instances above $3/4$. We construct hard instances in four native
> layers, embed them in typical schedules, and interpolate along Cayley paths using a rational
> linear-program decoder. A finite $192$-gate alphabet preserves the collision law exactly. Both
> guarantees use logarithmic native fermionic depth between arbitrary mode pairs and $O(n\log n)$
> gates, replacing the global-Haar construction's quadratic budget. The accuracy proved is finer
> than the $1/N$ scale, where $N=\binom{n}{n/2}$, required by sampling-to-counting; hardness of
> sampling within constant total-variation distance remains open.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

