---
aliases: ["On Euclidean Diameter in Dynamic Streams"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.33139"
url: "http://arxiv.org/abs/2611.33139v1"
published: "2026-11-24T18:55:53Z"
ingested: "2026-11-25T16:45:53Z"
authors:
  - "Jeff Giliberti"
  - "MohammadTaghi Hajiaghayi"
---

# On Euclidean Diameter in Dynamic Streams

## Abstract

> We give a streaming algorithm for maintaining the diameter of a high-dimensional Euclidean point
> set under arbitrary insertions and deletions that achieves update time polylogarithmic in the
> number of points and polynomial in the dimension. For every fixed $c>\sqrt3$, there is an $ε_c >
> 0$ such that our one-pass algorithm uses $\tilde O(N^{1-ε_c}\poly(d))$ space, has worst-case
> update time $\poly(d,\log N)$, and maintains a factor-$c$ pair witness. On the hardness side, we
> prove that every constant-factor approximation requires polynomial memory even on short dynamic
> streams: a factor-$c$ approximation needs $N^{Ω(1/(c^2\log(c+1)))}$ space on streams of at most
> $2N-1$ updates. Our upper bound combines a geometric hull, Gaussian hashing through successively
> smaller caps, and local and global rebuilding schedules. Every update changes only one leaf of
> the hash hierarchy, while the answer is maintained through small variance certificates. The
> lower bound is based on a communication complexity argument. Together, these results separate
> the polynomial memory regime from the time needed to process an update.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

