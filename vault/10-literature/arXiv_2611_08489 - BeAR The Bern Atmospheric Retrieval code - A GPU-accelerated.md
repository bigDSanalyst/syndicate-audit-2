---
aliases: ["BeAR: The Bern Atmospheric Retrieval code - A GPU-accelerated framework for low-resolution, high-resolution, and joint retrievals of exoplanet atmospheres"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.08489"
url: "http://arxiv.org/abs/2611.08489v1"
published: "2026-11-05T18:59:48Z"
ingested: "2026-11-06T13:43:03Z"
authors:
  - "Esther Wang"
  - "Daniel Kitzmann"
  - "H. Jens Hoeijmakers"
  - "Joost P. Wardenier"
  - "Helena Lecoq-Molinos"
---

# BeAR: The Bern Atmospheric Retrieval code - A GPU-accelerated framework for low-resolution, high-resolution, and joint retrievals of exoplanet atmospheres

## Abstract

> We present BeAR, the Bern Atmospheric Retrieval code and successor of Helios-r, and its new
> high-resolution cross-correlation framework for emission and transmission spectra. BeAR performs
> joint retrievals by adding the log-likelihoods of high- and low-resolution data computed from
> the same model atmosphere. The framework implements established cross-correlation log-
> likelihoods, with the line-depth scaling either fitted analytically or sampled as a free
> parameter, their per-pixel generalization, fast model filtering, and model re-injection adapted
> to this filtering. The forward model and likelihood run entirely on a graphics processing unit
> (GPU). One forward model takes about 1 ms on an NVIDIA GH200, allowing millions of models per
> minute on a GPU cluster. In separate retrievals of Gemini South/IGRINS and JWST/NIRSpec dayside
> spectra of the hot Jupiter WASP-77Ab, BeAR reproduces published abundances, C/O ratios, and
> metallicities to within 1.5 sigma, the preference for 13CO, and the thermal structure and line
> contrast to within 1 sigma. The joint retrieval confirms a sub-solar metallicity and a near-
> solar C/O ratio. A full IGRINS retrieval with 17 free parameters takes 27 to 42 minutes on a
> single NVIDIA GeForce RTX 5080 or about 14 minutes on eight RTX 4090 GPUs. Injection--recovery
> tests show that the posteriors underestimate the uncertainties of abundance ratios by about a
> factor of two.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

