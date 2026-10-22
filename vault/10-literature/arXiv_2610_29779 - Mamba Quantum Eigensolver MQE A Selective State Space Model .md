---
aliases: ["Mamba Quantum Eigensolver (MQE): A Selective State Space Model for Scalable Ground State Simulations in Quantum Chemistry"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.29779"
url: "http://arxiv.org/abs/2610.29779v1"
published: "2026-10-21T14:07:45Z"
ingested: "2026-10-22T11:07:59Z"
authors:
  - "G. X. A. Petronilo"
  - "M. R. Araújo"
  - "Erico S. Teixeira"
  - "Clebson Cruz"
---

# Mamba Quantum Eigensolver (MQE): A Selective State Space Model for Scalable Ground State Simulations in Quantum Chemistry

## Abstract

> Predicting molecular electronic structure using Quantum Computing approaches is a challenge in
> Computational Chemistry. Traditional Variational Quantum Eigensolvers (VQEs) are typically
> hindered by optimization challenges. The alternative Generative Quantum Eigensolver (GQE)
> mitigates this by reformulating ground-state search as discrete sequence generation, but its
> Transformer backbone suffers from quadratic computational complexity, bottlenecking scalability
> for larger molecules. To address this, we introduce the Mamba Quantum Eigensolver (Mamba-QE),
> which replaces the Transformer with a Selective State Space Model (SSM) to process operator
> sequences with linear $\mathcal{O}(L)$ complexity. Additionally, we integrate a distance-
> conditioned mechanism enabling the direct prediction of complete potential energy surfaces
> (PES). Evaluated on the $H_2$ molecule, Mamba-QE reproduces Full Configuration Interaction (FCI)
> reference energies well within chemical accuracy, achieving an energy error below
> $3\times10^{-6}$ Ha across 16 geometries with zero variational violations. Mamba-QE maintains
> high expressive power while establishing a robust, scalable foundation for quantum simulations
> of complex molecular systems.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

