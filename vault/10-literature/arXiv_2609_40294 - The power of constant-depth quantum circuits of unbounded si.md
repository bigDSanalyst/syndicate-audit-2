---
aliases: ["The power of constant-depth quantum circuits of unbounded size"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.40294"
url: "http://arxiv.org/abs/2609.40294v1"
published: "2026-09-30T17:50:16Z"
ingested: "2026-10-01T12:24:51Z"
authors:
  - "Sergii Strelchuk"
  - "Sathyawageeswar Subramanian"
  - "Máté Weisz"
---

# The power of constant-depth quantum circuits of unbounded size

## Abstract

> Classical circuits with unbounded fan-in can compute any Boolean function in constant depth when
> their size is unrestricted. We ask whether removing the restrictions on circuit size and
> ancillary qubits also allows quantum circuits built from arbitrary single-qubit gates and
> generalised Toffoli gates to implement every unitary in constant depth. We give exact constant-
> depth constructions for arbitrary permutations of computational basis states, diagonal unitaries
> and the preparation of arbitrary pure states. These connect quantum state preparation to
> reversible classical computation and the preparation of probability distributions. With fanout
> in the gate set, they use exponentially many gates and ancillary qubits and return all ancillary
> qubits to zero. Replacing fanout by an exact circuit over the original gate set preserves
> constant depth, although the size bounds can become doubly exponential. The implementation of
> arbitrary unitaries in constant depth remains open. We give equivalent formulations in terms of
> copying the vectors of a specified orthonormal basis, extracting their labels and implementing
> restricted families of unitaries. We also reduce arbitrary unitary implementation to that of
> traceless unitary involutions using one additional clean qubit. With adaptive measurements, gate
> teleportation gives depth proportional to the level of a gate in the Clifford hierarchy. Towards
> arbitrary unitary implementation in constant depth, we use port-based teleportation: for input
> dimension $d$ and $M\geq d^2-1$ ports, we construct a unitary circuit of depth $O(\sqrt d)$,
> independent of $M$ and including resource preparation and port selection, with entanglement
> fidelity at least $(1-(d^2-1)/(2M))^2$. Thus, at fixed $d$, the approximation can be made
> arbitrarily accurate without increasing depth. Whether the dependence on $d$ can also be removed
> remains open.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

