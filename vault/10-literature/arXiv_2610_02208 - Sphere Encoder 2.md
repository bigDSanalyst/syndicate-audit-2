---
aliases: ["Sphere Encoder 2"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.02208"
url: "http://arxiv.org/abs/2610.02208v1"
published: "2026-10-01T17:59:58Z"
ingested: "2026-10-02T11:51:31Z"
authors:
  - "Kaiyu Yue"
  - "Sean McLeish"
  - "Ruchit Rawal"
  - "Brian Bartoldson"
  - "Menglin Jia"
  - "Tom Goldstein"
---

# Sphere Encoder 2

## Abstract

> Sphere Encoder is an autoencoder that generates images by decoding random points from a high-
> dimensional latent sphere. We identify two limitations of the original formulation that reduce
> its generation quality. First, random points concentrate near the equator relative to the pole
> on an encoded latent, but the training rotation never reaches this region, leaving a gap that
> limits one-step generation. Second, training for generation with pixel-wise reconstruction loss
> encourages the decoder to average over plausible images, producing blurry images that lack high-
> frequency details. We present Sphere Encoder 2 to address both limitations, substantially
> improving image generation quality while maintaining the speed and simplicity of a autoencoder.
> Models are released at \href{https://github.com/kaiyuyue/sphere2}{github.com/kaiyuyue/sphere2}.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

