---
aliases: ["Quantum Circuits for Variable-Coefficient Vlasov Dynamics via Schrödingerisation"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.23405"
url: "http://arxiv.org/abs/2610.23405v1"
published: "2026-10-16T13:01:12Z"
ingested: "2026-10-19T12:05:19Z"
authors:
  - "Fong Yew Leong"
  - "Dax Enshan Koh"
  - "Wei-Bin Ewe"
  - "Qiubo Chen"
  - "Zhun-Yong Ong"
---

# Quantum Circuits for Variable-Coefficient Vlasov Dynamics via Schrödingerisation

## Abstract

> High-dimensional Vlasov equations present promising use cases for quantum simulation, but their
> transport coefficients must be implemented coherently in order to preserve a compact quantum
> representation. We develop explicit Schrödingerised circuits for prescribed external field
> Vlasov dynamics without classical field updates. In 1D1V, velocity-dependent streaming is
> compiled directly from the encoded velocity register, while a non-linear cubic field is
> evaluated using reversible fixed-point arithmetic. For fixed polynomial degree, the field
> workspace scales linearly with the coordinate register width, while the field evaluation
> subroutine has polynomial depth. As a proof of concept, we simulate a minimal coupled 3D3V
> anharmonic Penning system and realise mixed electric-field terms and transverse magnetic
> coupling on a six-dimensional phase space in agreement with classical calculations. Resource
> analysis shows approximately linear growth with the number of time steps, while identifying the
> auxiliary register as the dominant depth bottleneck. Structured preparation and register
> recovery of the auxiliary state reveal an interplay between loading cost and readout. Together,
> our algorithm demonstrates a fully coherent quantum simulation of high-dimensional Vlasov
> dynamics with variable coefficients and identifies the practical resource costs that must be
> controlled for large-scale quantum implementation.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

