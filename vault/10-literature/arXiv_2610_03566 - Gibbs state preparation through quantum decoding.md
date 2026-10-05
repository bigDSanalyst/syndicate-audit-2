---
aliases: ["Gibbs state preparation through quantum decoding"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.03566"
url: "http://arxiv.org/abs/2610.03566v1"
published: "2026-10-02T16:44:18Z"
ingested: "2026-10-05T13:34:01Z"
authors:
  - "Christophe Piveteau"
  - "Yihui Quek"
  - "M. Isabel Franco Garrido"
---

# Gibbs state preparation through quantum decoding

## Abstract

> We propose a Gibbs state preparation algorithm that exploits algebraic structure in the
> Hamiltonian. Our starting point is Hamiltonian Decoded Quantum Interferometry (HDQI), a recent
> algorithm that reduces Gibbs state preparation for Pauli Hamiltonians to decoding error-
> correcting codes. We introduce quantum decoding HDQI (QD-HDQI), replacing HDQI's coherent
> classical decoder by a quantum decoder that can exploit interference between different errors.
> For commuting Pauli Hamiltonians, our reduction is efficient and the associated quantum decoding
> problem corresponds to transmitting the associated symplectic code over i.i.d. pure-state
> classical-quantum channels. For uniformly random Hamiltonian signs, the vanishing-error
> threshold of an efficient decoder directly determines the lowest temperature that our algorithm
> can reach. Even using only classical decoders, this improves upon HDQI's achievable inverse
> temperature from linear to square-root in the correctable error fraction; quantum decoders can
> improve further by tolerating still stronger noise. A similar picture extends to the
> noncommuting regime previously handled by HDQI, where now the noise is correlated within small,
> independent blocks. We study two such quantum decoders in our QD-HDQI Gibbs sampling framework.
> The first, based on unambiguous state discrimination, works efficiently for arbitrary binary
> linear codes. However, we "dequantize" this strategy for commuting Hamiltonians, contributing a
> classical rejection sampler that matches its temperature threshold. The second is belief
> propagation with quantum messages (BPQM), a quantum generalization of classical belief
> propagation. We show that for certain dilute spin glasses, BPQM's decoding threshold exceeds the
> Shannon limit for classical decoding, reaching temperatures inaccessible to any classical
> decoder within our framework.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

