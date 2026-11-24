---
aliases: ["How Far Can Linear Go? BiPert, a Unified Framework for Single-Cell Perturbation Modelling"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.31227"
url: "http://arxiv.org/abs/2611.31227v1"
published: "2026-11-23T18:58:32Z"
ingested: "2026-11-24T16:56:39Z"
authors:
  - "Abhishek Sharma"
  - "Aleksej Zelezniak"
---

# How Far Can Linear Go? BiPert, a Unified Framework for Single-Cell Perturbation Modelling

## Abstract

> Understanding how genetic perturbations affect cellular behaviour is essential for studying gene
> function and regulatory mechanisms. Large-scale CRISPR screens measure these effects across
> thousands of genes, but cover relatively few cellular contexts. Predicting perturbation
> responses in unseen cell types and identifying perturbed genes from their transcriptional
> effects therefore remain challenging. Here, we show that both tasks can be addressed through a
> common linear decomposition of transcriptional responses into shared and perturbation-specific
> components. Building on this principle, we introduce BiPert, a simple linear framework for both
> forward perturbation prediction and inverse identification. For forward prediction, BiPert
> outperforms existing methods that use no external biological knowledge when predicting gene
> expression changes in unseen cell lines. Its few-shot extension, BiPert-FS, adapts to new cell
> lines using as few as ten measured perturbations. For inverse identification, BiPert-ID
> identifies perturbed genes from single-cell expression profiles, outperforming deep-learning
> methods in unseen cell lines and donors. We further show that perturbations whose effects
> transfer more consistently across cellular contexts are also easier to identify, even after
> controlling for perturbation effect size. Together, these results establish a connection between
> perturbation transfer and identification, and demonstrate that simple linear models provide
> strong, interpretable baselines for both tasks.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

