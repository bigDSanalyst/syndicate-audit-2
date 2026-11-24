---
aliases: ["Mitigating drift in spin-qubit control with calibration-insensitive pulses"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.30931"
url: "http://arxiv.org/abs/2611.30931v1"
published: "2026-11-23T16:20:24Z"
ingested: "2026-11-24T16:56:35Z"
authors:
  - "Mridul Pushp"
  - "Jonathan Hess"
  - "Seong Woo Oh"
  - "Vatsal K. Bandaru"
  - "Shize Che"
  - "Noah D. Johnson"
  - "Anthony J. Sigillito"
---

# Mitigating drift in spin-qubit control with calibration-insensitive pulses

## Abstract

> Silicon spin qubits offer fault-tolerant control fidelities in a platform that is compatible
> with commercial foundries, but device calibration drifts and control parameters must be retuned
> every few hours. Here, we replace conventional square control pulses with two drift-resilient
> pulse families: the adiabatic BIR-4 and the composite CORPSE. In a Si/SiGe quantum-dot device,
> we benchmark single-qubit gate sets built from each pulse against deliberate miscalibration. We
> find that BIR-4 offers a 99% Clifford fidelity over a factor of 2 change in drive power and
> CORPSE maintains similar fidelity over +/-0.9MHz of offset. When fully calibrated CORPSE offers
> a 99.97% fidelity per gate, on par with a calibrated square pulse. Starting with tuned pulses,
> we then track errors using gate-set tomography for ten days without recalibration. BIR-4 holds
> its rotation angle to 0.3 degrees throughout, including across a 1.3MHz frequency jump. Our
> results demonstrate that these pulses can maintain high-fidelity operations without constant
> recalibration, mitigating the need for constant tuning, which is a key bottleneck in scaling
> quantum-dot-based quantum processors.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

