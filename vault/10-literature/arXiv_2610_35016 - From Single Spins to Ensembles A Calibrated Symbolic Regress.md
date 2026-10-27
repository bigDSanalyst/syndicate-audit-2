---
aliases: ["From Single Spins to Ensembles: A Calibrated Symbolic Regression Pipeline for NV Spectroscopy"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.35016"
url: "http://arxiv.org/abs/2610.35016v1"
published: "2026-10-26T08:29:07Z"
ingested: "2026-10-27T11:34:59Z"
authors:
  - "Evan Zhang"
  - "Zhenghang Zhi"
  - "Zewei Wang"
  - "Zeheng Wang"
---

# From Single Spins to Ensembles: A Calibrated Symbolic Regression Pipeline for NV Spectroscopy

## Abstract

> Characterizing nitrogen-vacancy (NV) ensembles requires connecting their collective spectra to
> individual centers that experience different local environments. We develop a symbolic-
> regression pipeline that carries single-center spin structure into a calibrated ensemble model
> by generating individual spectral responses and combining them with explicit weights. A
> constrained search selects Hermitian operator terms from single-center optically detected
> magnetic resonance spectra, fits their coefficients, and retains the selected expressions as
> source models for the ensemble. Ensemble calibration then accounts for resonance shifts, local
> disorder, orientation, and optical response while keeping the individual spectral contributions
> accessible. On public single-center and ensemble data, the zero-field ensemble held-frequency
> root-mean-square error decreases from 0.008835 to 0.003872 in normalized photoluminescence, a
> 56.2% improvement over matched uncorrected composition. In controlled QuTiP ensembles of 128
> sites spanning four NV orientations, models calibrated at 0 and 3 mT predict an independently
> held-out 5.17 mT spectrum with errors of 0.000207-0.000228 across three random seeds, comparable
> to the 0.000200 noise standard deviation. Resolving the simulated response into its individual-
> center contributions shows how local spectral diversity combines into the ensemble line shape.
> By retaining the source Hamiltonians while calibrating sample-dependent spectral differences,
> the pipeline connects local spin physics to collective optical readout and makes the
> contributions to an ensemble line shape available for physical interpretation.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

