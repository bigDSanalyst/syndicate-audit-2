---
aliases: ["Adaptive Hamiltonian Identification via Quantum Reinforcement Learning under Non-Stationary Dynamics"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.26241"
url: "http://arxiv.org/abs/2611.26241v1"
published: "2026-11-19T15:20:21Z"
ingested: "2026-11-20T14:52:10Z"
authors:
  - "Jawaher Kaldari"
  - "Saif Al-Kuwari"
---

# Adaptive Hamiltonian Identification via Quantum Reinforcement Learning under Non-Stationary Dynamics

## Abstract

> Accurate identification of the Hamiltonian governing a quantum system is important for quantum-
> system characterization, device calibration, simulation, and reliable operation of quantum
> hardware. In practical systems, however, the governing dynamics may vary over time because of
> parameter drift, changing control conditions, or transitions between operating regimes. In this
> work, we formulate Hamiltonian identification as a quantum reinforcement learning (QRL) problem
> in which a quantum agent processes sequential quantum-state observations and estimates the
> governing Hamiltonian parameters. We first consider stationary dynamics using a Vanilla-QRL
> agent and then introduce a recurrent GRU-QRL architecture to track non-stationary dynamics. The
> framework is evaluated on transverse-field Ising model systems under stationary dynamics, abrupt
> Hamiltonian switching, rapidly changing Hamiltonians, random switch locations over longer
> trajectories, and gradual Hamiltonian drift. We further compare the proposed approach with a
> Quantum Graph Recurrent Neural Network (QGRNN) baseline and evaluate frozen policies on unseen
> trajectories. Results show that both approaches accurately reconstruct stationary Hamiltonians,
> while GRU-QRL provides substantially improved tracking under non-stationary dynamics. These
> results demonstrate the potential of recurrent QRL as an adaptive system-identification tool for
> monitoring time-varying quantum systems.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

