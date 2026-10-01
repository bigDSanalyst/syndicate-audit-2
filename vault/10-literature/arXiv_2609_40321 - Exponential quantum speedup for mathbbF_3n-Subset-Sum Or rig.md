---
aliases: ["Exponential quantum speedup for $\\mathbb{F}_3^n$-Subset-Sum? Or, rigorous classical algorithms for Binary-Error LWE"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.40321"
url: "http://arxiv.org/abs/2609.40321v1"
published: "2026-09-30T17:54:52Z"
ingested: "2026-10-01T12:24:51Z"
authors:
  - "Robin Kothari"
  - "Tony Metger"
  - "Ryan O'Donnell"
  - "Noah Shutty"
  - "Kewen Wu"
---

# Exponential quantum speedup for $\mathbb{F}_3^n$-Subset-Sum? Or, rigorous classical algorithms for Binary-Error LWE

## Abstract

> We study vector subset sum over $\mathbb{F}_3^n$: given $m$ random vectors from
> $\mathbb{F}_3^n$, find a nonempty subset that sums to zero; the smaller $m$, the more difficult
> it is to find such a subset. Chen, Liu, and Zhandry (EUROCRYPT'22) introduced an efficient
> quantum algorithm that solves this problem when $m\approx n^2/2$, where a naive classical
> algorithm would require exponential time. Subsequently, Kothari, O'Donnell, and Wu (STOC'2026)
> gave an efficient classical algorithm that only requires $m \approx n^2/3$ vectors, thus
> removing the hope for an exponential quantum advantage in this parameter regime. Using the
> framework of Chen, Liu, and Zhandry, we give quantum algorithms that require much fewer input
> vectors, renewing the possibility of an exponential quantum speedup: for any fixed $ε>0$, our
> quantum algorithm solves $\mathbb{F}_3$-subset sum in polynomial time with $m=ε\cdot n^2$
> vectors. More generally, we establish a full sample--time tradeoff that interpolates between
> exponential and polynomial runtime. The main ingredient is a deterministic classical algorithm
> for the binary-error Learning-with-Errors problem, which is of independent cryptographic
> interest. For this, we rigorously establish a sample--time tradeoff that was predicted by
> earlier algebraic heuristics. For vector subset sums over larger fields, we also significantly
> improve classical algorithms in Kothari, O'Donnell, and Wu (STOC'2026).

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

