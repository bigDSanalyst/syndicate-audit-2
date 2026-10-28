---
aliases: ["Prepare-and-measure quantum key distribution from a bound on information leakage"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.37296"
url: "http://arxiv.org/abs/2610.37296v1"
published: "2026-10-27T14:16:59Z"
ingested: "2026-10-28T12:05:15Z"
authors:
  - "Abhishek Mishra"
  - "Michele Masini"
  - "Maria Balanzó-Juandó"
  - "Armin Tavakoli"
  - "Stefano Pironio"
---

# Prepare-and-measure quantum key distribution from a bound on information leakage

## Abstract

> Every quantum key distribution (QKD) protocol must limit the information available outside the
> users' laboratories. In device-independent QKD this is essentially the only assumption made on
> the devices. In a prepare-and-measure setting it cannot be imposed strictly, since the sender's
> device must emit a signal that depends on her private input. The natural replacement, and a
> minimal one, is a leakage bound: a bound on how much information about the input leaves the
> sender's laboratory, through the intended signal or through any side channel. We ask how far
> this unavoidable requirement can replace a detailed model of the source. We show that this
> single bound, quantified by the probability of guessing the input from everything the source
> emits, suffices to prove security against collective attacks. In our analysis, nothing is
> assumed about the precise form of the emitted states, their dimension, energy or purity, nor
> about the receiver's measurement device, beyond the standard requirement that it does not leak
> Bob's data. The standard B92 and BB84 protocols do not certify any key under this minimal
> leakage bound assumption. But closely related protocols can and, in the ideal limit, achieve one
> secret bit per key round. For noisy implementations, we compute key rates using semidefinite
> programming relaxations. Our best protocols tolerate visibilities down to 0.84, corresponding to
> an 8% quantum bit error rate, compared with the 11% threshold of standard device-dependent BB84.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

