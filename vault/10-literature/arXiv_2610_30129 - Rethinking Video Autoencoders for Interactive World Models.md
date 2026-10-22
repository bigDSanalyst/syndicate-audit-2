---
aliases: ["Rethinking Video Autoencoders for Interactive World Models"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.30129"
url: "http://arxiv.org/abs/2610.30129v1"
published: "2026-10-21T17:58:11Z"
ingested: "2026-10-22T11:08:02Z"
authors:
  - "Adrien Ramanana Rahary"
  - "Yutong Bai"
  - "Nicolas Dufour"
  - "Patrick Pérez"
  - "David Picard"
---

# Rethinking Video Autoencoders for Interactive World Models

## Abstract

> Video world models predict future frames from past frames and actions. They serve as simulators
> in which agents train, plan or are evaluated, and that humans can control interactively. They
> generate in the latent space of a video autoencoder, whose compression sets their cost per frame
> and how long each action waits to take effect. Yet world models often reuse the autoencoders of
> text-to-video generators, built for offline generation with no agent waiting and, without their
> training data and code, not retrainable at another compression. We therefore ask how, where and
> how much a world model should compress. We build CADRE, an open family of causal diffusion
> representation autoencoders spanning multiple spatio-temporal compressions. Its members differ
> only in a small bottleneck on frozen features and share a diffusion decoder self-distilled to
> one or a few steps. We train the same world model on each autoencoder in two domains,
> manipulation and navigation, with two environments each. CADRE forms most of the latency-quality
> frontier, especially with a moving camera. Our study also leads to four findings. At strong
> compression, a diffusion decoder is sharper than perceptual regression. In robot manipulation,
> temporal compression is more effective in the autoencoder than in the world model. Manipulation
> and navigation call for opposite compressions: temporal compression costs little when the camera
> is still, and spatial compression when it moves. Surprisingly, with a still camera, coarser
> spatial tokens hurt motion far more than image quality. Code, models and a live demo are at
> https://kyutai.org/blog/2026-10-21-cadre

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

