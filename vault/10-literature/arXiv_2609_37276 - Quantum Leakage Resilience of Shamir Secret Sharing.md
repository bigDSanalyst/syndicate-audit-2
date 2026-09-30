---
aliases: ["Quantum Leakage Resilience of Shamir Secret Sharing"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.37276"
url: "http://arxiv.org/abs/2609.37276v1"
published: "2026-09-29T11:19:06Z"
ingested: "2026-09-30T11:54:04Z"
authors:
  - "Rishabh Batra"
  - "Fuyuki Kitagawa"
  - "Ryo Nishimaki"
  - "Takashi Yamakawa"
---

# Quantum Leakage Resilience of Shamir Secret Sharing

## Abstract

> We initiate the study of quantum leakage resilience of unmodified Shamir secret sharing over
> prime fields. A well-studied leakage model for Shamir's secret sharing classically is single-bit
> local leakage from each share. We consider its quantum analogue where, for each party, a local
> leakage channel takes as input the party's share and outputs a leaked qubit. Without preshared
> entanglement, we show that the distinguishing advantage is $2^{-Ω(n)}$ when the threshold rate
> $t/n=τ$ exceeds $τ_\star\approx0.73339$ by a fixed positive margin. More generally, we allow
> disjoint entangled blocks of any fixed maximum size where there is no entanglement between
> different blocks or with the adversary, and each block emits at most a fixed number of qubits.
> Security holds when the threshold rate is high enough (sufficiently close to one). We then allow
> a specified set of devices to share entanglement with the adversary. We show that security holds
> even when a linear number of devices ($αn$ for small $α>0$) share entanglement with each other
> and with the adversary for a large enough threshold rate. As a complementary negative result, we
> also show that even classical single-bit leakage makes Shamir scheme insecure if we allow
> arbitrarily large entanglement between the leakage devices. A GHZ state shared by exactly $t$
> leakage devices makes even classical one-bit leakage insecure, without any entanglement with the
> adversary. In this attack, each participating device emits only one classical bit, and their
> joint parity distinguishes any chosen pair of secrets with a constant advantage. Thus, for fixed
> threshold rates above $τ_\star$, the maximum number of devices that may share arbitrary
> entanglement with one another and with the adversary while preserving security is linear in $n$
> up to constant factors, although the optimal support fraction remains open.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

