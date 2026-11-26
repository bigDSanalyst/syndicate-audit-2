---
aliases: ["A gene informed benchmark for BioScoring of pathology foundation models"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.34930"
url: "http://arxiv.org/abs/2611.34930v1"
published: "2026-11-25T18:59:13Z"
ingested: "2026-11-26T16:21:38Z"
authors:
  - "Paul Vilars"
  - "Vincent Quoc-Huy Trinh"
  - "Maria Vakalopoulou"
  - "Dimitris Samaras"
  - "Stergios Christodoulidis"
  - "Mahdi S. Hosseini"
---

# A gene informed benchmark for BioScoring of pathology foundation models

## Abstract

> Pathology foundation models are usually compared by their performance on downstream tasks such
> as classification and retrieval. While such benchmarks measure how useful a model is, they
> provide no insight into the biology it represents. We introduce BioScore, a benchmark that
> quantifies how well an image encoder captures cell identities, with spatial transcriptomics of
> the same tissue as the reference. A sparse autoencoder splits the encoder's patch embeddings
> into sparse features, which we cluster into a fixed number of groups. BioScore then measures,
> for each of 52 cell identities defined by marker genes, how specifically one group follows the
> identity's expression over the tissue. Because the autoencoder training is fully unsupervised, a
> match shows that the model represents the cell identity from the image alone. We score 8
> pathology foundation models and 3 natural-image models. Every pathology model scores above every
> natural-image model (0.299--0.371 \vs 0.214--0.232), and paired tests separate three tiers among
> the pathology models. Unlike a supervised probe, BioScore needs no labels, builds its reference
> from the data and scores even from few sections, yet it ranks the encoders as a probe does. Its
> per-identity breakdown indicates which cell identities each encoder captures or misses.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

