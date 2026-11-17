---
aliases: ["Limited-Memory First-Order Methods: Identification, Reconstruction, $H$-Duality and Application to Optimized Methods"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.21611"
url: "http://arxiv.org/abs/2611.21611v1"
published: "2026-11-16T18:59:59Z"
ingested: "2026-11-17T15:28:29Z"
authors:
  - "Pierre Vernimmen"
  - "François Glineur"
  - "Baptiste Goujaud"
  - "Adrien B. Taylor"
---

# Limited-Memory First-Order Methods: Identification, Reconstruction, $H$-Duality and Application to Optimized Methods

## Abstract

> In general, linear-span first-order methods add at every iteration a combination of all observed
> gradients to the previous iterate. However, many methods of interest can be implemented in a way
> that requires storing only a few auxiliary vectors, instead of all past gradients. We call such
> methods limited-memory first-order methods. A given fixed-coefficient first-order method can be
> described by a lower triangular coefficient matrix, which expresses each step as a combination
> of previous gradients. We show that the minimum number of running sums required to implement a
> method is equal to the minimum rank of a completion of the strict lower triangular part of its
> coefficient matrix, and propose a reconstruction algorithm. Moreover, taking the $H$-dual of a
> method, which reflects the coefficient matrix across its anti-diagonal, preserves its memory and
> translates into a permutation and time-reversal on the coefficients of the running sum
> recurrences. We apply our results to two optimized first-order methods for smooth strongly
> convex functions. First, our reconstruction applied to a method numerically designed by Shu and
> Wang reveals a recurrence with one auxiliary vector, which is related to the Triple Momentum
> Method (TMM) of Van Scoy, Freeman and Lynch with a particular initialization. We prove that the
> reconstructed method, called TMM-GD, is minimax optimal at every horizon for the final distance
> to the minimizer relative to the initial gradient norm. Second, the Information-Theoretic Exact
> Method (ITEM) of Taylor and Drori, optimal for the final distance relative to the initial one,
> is known to be memory one. We give an explicit recurrence with one auxiliary vector for its
> $H$-dual, called ITEM-GG, and prove that ITEM-GG is the unique minimax optimal nonadaptive
> linear-span method for the final gradient norm relative to the initial one.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

