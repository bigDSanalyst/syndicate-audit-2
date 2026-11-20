---
aliases: ["Classically Trained Quantum Generative Models with Shared Training and Fine Tuning for Quantum Matter"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.26577"
url: "http://arxiv.org/abs/2611.26577v1"
published: "2026-11-19T18:42:29Z"
ingested: "2026-11-20T14:52:10Z"
authors:
  - "Mario Herrero-Gonzalez"
  - "Elham Kashefi"
  - "Mina Doosti"
---

# Classically Trained Quantum Generative Models with Shared Training and Fine Tuning for Quantum Matter

## Abstract

> Ground-state measurement statistics characterize quantum matter. Selected correlations can guide
> the classical training of a quantum sampler even when sampling the full distribution is
> difficult. We ask whether training across related ground-state distributions helps the sampler
> reproduce their correlations more accurately. We train a hypernetwork to map Hamiltonian
> parameters to circuit angles, sharing information across the phase diagram before local fine-
> tuning with additional reference data for quantum deployment. For classical training, we derive
> an unbiased Monte Carlo estimator of Fourier coefficients for circuits built from general Pauli
> rotations, with a cost that depends on the circuit generators. We also introduce a CDF-KL loss
> for comparing selected marginals. We study the Haldane Hamiltonian and transverse-field Ising
> model, using an automated search to select reference calculations near phase transitions. On the
> twelve-site chain, the adaptively pretrained hypernetwork matches the independent fits' final
> mean total variation distance in fewer local updates and continues to a lower error. On a
> 1,024-site chain and a 4 by 256 lattice, the fine-tuned circuits have lower squared maximum mean
> discrepancy from the reference distributions than the independent circuits at the evaluated
> point in each geometry. These results motivate shared training for preparing quantum samplers
> across a phase diagram and local fine-tuning.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

