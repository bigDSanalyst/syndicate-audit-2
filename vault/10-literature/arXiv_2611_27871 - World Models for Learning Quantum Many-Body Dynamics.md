---
aliases: ["World Models for Learning Quantum Many-Body Dynamics"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.27871"
url: "http://arxiv.org/abs/2611.27871v1"
published: "2026-11-20T17:15:31Z"
ingested: "2026-11-23T17:21:01Z"
authors:
  - "Yuan Wang"
  - "Oleksandr Kyriienko"
---

# World Models for Learning Quantum Many-Body Dynamics

## Abstract

> We propose using world models for learning Hamiltonians from measured dynamics of a quantum
> computer or simulator. Implicitly, the parameters of a Hamiltonian are encoded in how the
> measured few-body observables evolve. By using a joint-embedding predictive architecture (JEPA)
> to perform prediction in latent space, we show that the device Hamiltonian can be efficiently
> inferred from noisy measurements. We train a spatiotemporal encoder and predictor with
> approximately $2.7$ million trainable weights using a single objective, to predict the
> representation of the next window of measurements from the previous one. The network is thereby
> driven to retain the reproducible dynamics and discard shot noise. We recover the field and
> coupling maps of a two-dimensional Ising lattice in real and imaginary time, and the disorder
> map of a one-dimensional Heisenberg chain of $100$ sites. In every settings the encoder achieves
> lower error than a masked autoencoder and than the same encoder left untrained. It also
> outperforms the same regression head applied directly to time-averaged observables, by factors
> of $4.4$ to $30$. We establish latent prediction as a practical self-supervised objective for
> learning from measurements of quantum dynamics.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

