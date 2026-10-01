---
aliases: ["On The Simplest Quantum-Secure Block Cipher"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.40350"
url: "http://arxiv.org/abs/2609.40350v1"
published: "2026-09-30T17:59:10Z"
ingested: "2026-10-01T12:24:55Z"
authors:
  - "Gorjan Alagic"
  - "Joseph Carolan"
  - "Christian Majenz"
  - "Saliha Tokat"
---

# On The Simplest Quantum-Secure Block Cipher

## Abstract

> Pseudorandom permutations are ubiquitous in theoretical and applied cryptography. PRPs that
> offer security even against adversaries making quantum queries are of increasing interest, and
> used in applications ranging from constructing pseudorandom unitaries to separating SZK from
> BQP. A successful framework for constructing classically-secure PRPs is the key-alternating
> Even-Mansour approach, which interleaves applications of public permutations with additions of
> round keys. The single-round construction is already classically secure in the ideal permutation
> model (IPM), with added rounds offering improved concrete security. However, in the quantum-
> query setting, the status of this framework is presently unclear. A simple quantum-query attack
> based on Simon's algorithm breaks the one-round cipher. For two or more rounds, security is only
> known against non-adaptive adversaries who must prepare all queries in advance. In this work, we
> show that the two-round Even-Mansour cipher is information theoretically secure in the IPM
> against adversaries making polynomially-many adaptive forward and inverse quantum queries to all
> available oracles. Our proof uses compressed permutation oracles and a specially crafted
> isometry relating the ideal and real experiments. We also show that this construction is
> minimal, in the sense that essentially any cipher constructed via a single call to a public
> permutation is quantumly insecure.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

