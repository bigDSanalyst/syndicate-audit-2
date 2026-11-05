---
aliases: ["A Simple Subquadratic Cut Query Protocol for Directed Reachability"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.06906"
url: "http://arxiv.org/abs/2611.06906v1"
published: "2026-11-04T18:53:36Z"
ingested: "2026-11-05T13:58:04Z"
authors:
  - "Henry Fleischmann"
  - "Sagnik Mukhopadhyay"
  - "Swagato Sanyal"
---

# A Simple Subquadratic Cut Query Protocol for Directed Reachability

## Abstract

> We study $s$--$t$ reachability in an unweighted directed graph on $n$ vertices, accessed through
> a directed cut oracle: given $S\subseteq V$, the oracle returns the number of edges directed
> from $S$ to $V\setminus S$. Directed cut functions are submodular, and reachability asks whether
> the minimum $s$--$t$ cut has positive value. This connects the problem to the query complexity
> of submodular function minimisation. Whether or not reachability can be solved in truly
> subquadratic query complexity has been an outstanding open question for a decade. We give a
> simple algorithmic blueprint with two randomised implementations. The first uses $\widetilde
> O(n^{9/5})$ outgoing-cut queries; the second improves this bound to $\widetilde O(n^{5/3})$. The
> common idea is to construct an alternative orientation with the same underlying undirected graph
> and vertex-wise degree imbalances, thereby preserving reachability. We first approximate the
> target imbalances using an averaging and rounding procedure, then correct the remaining error
> with a flow. An earlier manuscript, made available in August 2026 in an online AI repository,
> reports an $\widetilde O(n^{3/2})$ query bound. Our contribution is a simple and comprehensible
> alternative approach that already achieves a polynomial saving over quadratic query complexity.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

