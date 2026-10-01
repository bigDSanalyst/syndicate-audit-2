---
aliases: ["Fast Cliffords When Your Quantum Memory Is Full"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.40144"
url: "http://arxiv.org/abs/2609.40144v1"
published: "2026-09-30T16:51:42Z"
ingested: "2026-10-01T12:24:51Z"
authors:
  - "Marten Folkertsma"
  - "Ian Mertz"
  - "Sergii Strelchuk"
  - "Sathyawageeswar Subramanian"
---

# Fast Cliffords When Your Quantum Memory Is Full

## Abstract

> Additional qubits can reduce the depth of a quantum circuit by providing workspace for parallel
> computation, but standard constructions assume that this workspace is initialized in a known
> state. In this work we study catalytic implementations, i.e. asking whether dirty qubits can
> instead be used provided that their joint state including any entanglement with other registers
> is restored exactly at the end of the computation. We show that every $n$-qubit Clifford circuit
> has a catalytic implementation of depth $O(\log n)$ using $O(n^2/\log^2 n)$ catalytic qubits and
> no clean qubits, matching the asymptotic depth achievable when clean workspace is available. We
> extend this approach to diagonal elements of any fixed level $C_k$ of the Clifford hierarchy,
> which admit catalytic implementations of depth $O(\log(n+1))$ with $O(n^k/\log(n))$ gates and
> $O(n^k/\log^2(n))$ catalytic qubits, as well as to semi-Clifford Gates.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

