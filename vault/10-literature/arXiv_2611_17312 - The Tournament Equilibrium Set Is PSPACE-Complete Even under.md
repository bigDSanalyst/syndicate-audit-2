---
aliases: ["The Tournament Equilibrium Set Is PSPACE-Complete, Even under Hereditary Uniqueness"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.17312"
url: "http://arxiv.org/abs/2611.17312v1"
published: "2026-11-12T18:57:05Z"
ingested: "2026-11-13T13:54:15Z"
authors:
  - "Ethan Dickey"
  - "Athina Terzoglou"
---

# The Tournament Equilibrium Set Is PSPACE-Complete, Even under Hereditary Uniqueness

## Abstract

> The tournament equilibrium set (TEQ), proposed by Schwartz in 1990, is a classical voting rule
> based on pairwise majority comparisons. Its definition is recursive: an alternative is judged by
> the alternatives that beat it, called its dominators, and by which of those dominators TEQ
> itself selects. Deciding whether a given alternative belongs to TEQ was known to be NP-hard and
> to lie in PSPACE. We close this gap by proving that the problem is PSPACE-complete. To our
> knowledge, this is the first PSPACE-completeness result for membership in a tournament solution.
> The hardness persists even when every nonempty subtournament has a unique minimal retentive set,
> the property conjectured by Schwartz to hold for all tournaments. Moreover, every such
> subtournament in our hard instances contains an alternative with at most three dominators. We
> prove that a single alternative with at most four dominators suffices both to guarantee
> uniqueness and to find a TEQ winner in $O(N^2)$ time. Thus, on our hard instances, finding one
> winner is efficient even though recognizing a specified winner is PSPACE-complete. We also study
> how the complexity changes with the dominator bound. If every nonempty subtournament has an
> alternative with at most one dominator, the entire TEQ can be computed in quadratic time;
> allowing two dominators makes membership NP-hard. Under the same condition with four dominators,
> all $t$ winners can be computed in $O(2^t N^2)$ time, where $N$ is the number of alternatives.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

