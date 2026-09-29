---
aliases: ["Fourier-Geometric Circuit Design for Gate and Entanglement Placement in Quantum Neural Networks"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.35489"
url: "http://arxiv.org/abs/2609.35489v1"
published: "2026-09-28T16:00:45Z"
ingested: "2026-09-29T12:06:17Z"
authors:
  - "Seungcheol Oh"
  - "Chaemoon Im"
  - "Daeyeun Kim"
  - "Soohyun Park"
  - "Vaneet Aggarwal"
  - "Mohsen Heidari"
  - "Joongheon Kim"
---

# Fourier-Geometric Circuit Design for Gate and Entanglement Placement in Quantum Neural Networks

## Abstract

> The output of a parameterized quantum circuit (PQC) can be expressed as a finite Fourier series
> whose accessible frequencies are fixed by the data-encoding gates. While the encoder determines
> which frequencies can appear, the corresponding Fourier coefficients depend on how the trainable
> and entangling gates are arranged. Although existing studies provide metrics for characterizing
> how gate structure affects Fourier coefficients, they do not translate these analyses into an
> explicit design criterion specifying how gates should be arranged to make a target coefficient
> reachable. In this paper, we provide such a criterion. Using the adjoint action of the encoding
> generator, we decompose operator space into two-dimensional invariant planes indexed by
> frequency and show that each Fourier coefficient is exactly a sum of bilinear projections of the
> effective state and observable onto the planes at that frequency. Because, for Pauli encodings,
> high-frequency planes are spanned by mixed multi-qubit Pauli strings, a target coefficient can
> contribute to the output only when local rotations and entangling layers are arranged so that
> both the effective state and observable acquire support on one of its planes. For Pauli readouts
> and commuting two-qubit entanglers, this yields a circuit design rule that specifies, for a
> given interaction graph, a placement of local rotations and entangling layers that makes a
> target Fourier coefficient reachable. Using a single encoding layer, we validate the proposed
> design through a placement ablation, regression tasks from PDEBench and physics-informed Maxwell
> field modeling, and further demonstrate its robustness to moderate simulated gate noise and
> damping.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

