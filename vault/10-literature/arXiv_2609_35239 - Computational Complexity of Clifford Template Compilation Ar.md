---
aliases: ["Computational Complexity of Clifford Template Compilation: Are Quantum Computers Useful for Compiling Quantum Circuits?"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.35239"
url: "http://arxiv.org/abs/2609.35239v1"
published: "2026-09-28T14:13:36Z"
ingested: "2026-09-29T12:06:17Z"
authors:
  - "Keisuke Fujii"
---

# Computational Complexity of Clifford Template Compilation: Are Quantum Computers Useful for Compiling Quantum Circuits?

## Abstract

> A Clifford template is a finite ordered family of repeatable Clifford operations, and an
> instantiation specifies how many times each operation is applied. The Clifford template
> compilation problem asks how to choose these repetition numbers so that the template realizes a
> target transformation of Pauli operators. This problem arises, for example, when searching for
> logical operations in quantum error correction using only Clifford operations permitted by
> physical or fault-tolerance constraints. Although forward Clifford dynamics is efficiently
> classically simulable, this inverse problem has sharp complexity transitions. For commuting
> templates with unrestricted integer exponents, feasibility lies in $\mathrm{NP}\cap\mathrm{BQP}$
> and a constructive quantum algorithm returns a particular solution together with the full
> exponent-relation lattice; already at $k=1$, recovering the repetition number contains finite-
> field discrete logarithm over $\mathbb{F}_{2^r}^{\times}$. In general, restricting every
> exponent to $\{0,1\}$ removes the Abelian-group closure and makes feasibility NP-complete for
> variable $k$, even for exactly commuting CNOT-only operations and X-type Paulis. For commuting
> self-inverse Clifford actions, both binary feasibility and recovery of one solution are
> classically polynomial-time solvable, but imposing a bound on the total repetition count is NP-
> complete, even for CNOT-only operations. These results reveal a rich complexity landscape within
> Clifford template compilation, spanning classically tractable cases, problems admitting quantum
> polynomial-time algorithms, and NP-complete variants.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

