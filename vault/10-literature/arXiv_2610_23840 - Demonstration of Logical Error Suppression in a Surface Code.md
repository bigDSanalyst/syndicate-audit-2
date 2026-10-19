---
aliases: ["Demonstration of Logical Error Suppression in a Surface Code Memory on a Cloud-Accessible IBM Superconducting Processor"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.23840"
url: "http://arxiv.org/abs/2610.23840v1"
published: "2026-10-16T17:56:53Z"
ingested: "2026-10-19T12:05:27Z"
authors:
  - "Shuwen Kan"
  - "Aaron Hoyt"
  - "Sean Garner"
  - "Ethan Vo"
  - "Adrian Harkness"
  - "Rod Rofougaran"
  - "Zefan Du"
  - "Chenxu Liu"
  - "Norm Tubman"
  - "Ying Mao"
  - "Samuel Stein"
---

# Demonstration of Logical Error Suppression in a Surface Code Memory on a Cloud-Accessible IBM Superconducting Processor

## Abstract

> Quantum error correction can suppress logical errors exponentially with code distance when
> physical noise is below threshold. Realizing this on hardware requires tight coordination among
> quantum gates, mid-circuit measurements, and qubit coherence. Device variation, noise asymmetry,
> and correlations across space and time complicate the translation of these capabilities into
> logical error suppression. Here, we study rotated surface-code memory on an IBM Nighthawk r2
> processor. Performance varies across tested processor placements, which we attribute to
> differences in qubit quality. We optimize the code by combining short readout, fused measurement
> and reset, and an XX echo on data qubits during ancilla readout. Compared with standard readout
> without reset or echo, the optimized syndrome extraction circuit reduces the median per-round
> logical error rate by factors of 3.8 in the X basis and 1.4 in the Z basis. In memory
> experiments of up to 150 rounds, the distance advantage weakens, alongside long-lived
> correlations that may reflect a persistent error component. Under our optimization recipe,
> increasing the protected distance from 3 to 6 while holding the other distance fixed reduces the
> per-round logical error rate from 0.53% to 0.24% in Z memory and from 0.52% to 0.22% in X
> memory. The corresponding error-suppression factors under maximum-likelihood decoding are 1.68
> and 1.85. These results connect circuit compilation and optimization to surface-code memory
> performance and limitations, and motivate QPU and QEC circuit codesign for fault-tolerant
> quantum computing primitives on current cloud hardware.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

