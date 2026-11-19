---
aliases: ["Map-Level Inference of Primordial Gravitational Waves from the CMB with Spherical Neural Networks"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.24939"
url: "http://arxiv.org/abs/2611.24939v1"
published: "2026-11-18T18:59:32Z"
ingested: "2026-11-19T15:13:40Z"
authors:
  - "Anto I. Lonappan"
  - "Adrian E. Bayer"
  - "Brian Keating"
  - "Kam Arnold"
  - "Giuseppe Puglisi"
  - "Ethan O. Nadler"
---

# Map-Level Inference of Primordial Gravitational Waves from the CMB with Spherical Neural Networks

## Abstract

> We train a spherical graph convolutional network to infer the tensor-to-scalar ratio $r$
> directly from multifrequency cosmic microwave background (CMB) $B$-mode maps on the cut sky. We
> test the network on simulations of a generic ground-based experiment including lensed CMB,
> inhomogeneous noise, and stochastic Galactic dust and synchrotron emission. We compare the
> network with a multifrequency bandpower likelihood built from the same 20,000 simulations used
> to train it. Working directly on the maps, with no power-spectrum estimation or component
> separation, the network reduces the root-mean-square error on $r$ by a factor of 1.3 and gives
> well-calibrated 68% intervals 1.2 times narrower than the likelihood with the same prior.
> Saliency maps show that the network learns to favor the deepest regions of the sky and the
> cleanest frequency channels without being given the survey depth. Both approaches are tied to
> the foreground model they are built on: the network generalizes to some alternative foreground
> models without retraining, but not to a three-dimensional dust model with line-of-sight
> variations. The network can be extended to marginalize over foreground models by training on a
> broad family, making direct map-level neural inference a promising route to $r$ for future
> $B$-mode analyses.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

