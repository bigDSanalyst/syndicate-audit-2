---
aliases: ["BRUCE (Bayesian Rio Urban Climate Estimator): spatiotemporal interpolation of air temperature from heterogeneous sensor networks for operational heat monitoring"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.26612"
url: "http://arxiv.org/abs/2611.26612v1"
published: "2026-11-19T18:57:20Z"
ingested: "2026-11-20T14:52:15Z"
authors:
  - "Ayrton Sena Gouveia"
  - "Rafael Santos de Oliveira"
  - "Lucas Menezes-Silva"
  - "Maira Alejandra Moreno Castillo"
  - "Felipe de Carvalho Vommaro Marincola"
  - "João Henrique de Araújo Morais"
  - "Valéria Saraceni"
  - "Gislani Mateus Oliveira Aguilar"
  - "Caroline Dias Ferreira"
  - "Oswaldo Gonçalves Cruz"
---

# BRUCE (Bayesian Rio Urban Climate Estimator): spatiotemporal interpolation of air temperature from heterogeneous sensor networks for operational heat monitoring

## Abstract

> Accurate characterization of intra-urban temperature variability is essential for heat-health
> surveillance, yet official monitoring networks are too sparse to resolve fine-scale gradients,
> particularly in Global South cities. We present BRUCE, a Bayesian hierarchical spatiotemporal
> model, fitted with the Integrated Nested Laplace Approximation (INLA) and a Stochastic Partial
> Differential Equation (SPDE) spatial component, that fuses four heterogeneous temperature
> sources for Rio de Janeiro, Brazil: official weather stations, low-cost IoT sensors, citizen-
> science personal weather stations and ERA5-Land reanalysis. The model accounts for class- and
> station-specific measurement bias and estimates a continuous spatial field that evolves day to
> day through an autoregressive (AR1) structure. Fitted independently to nine monthly windows
> (January, June, November; 2023--2025), the elevation coefficient was significant in all windows
> and of consistent magnitude in eight ($-$1.08 to $-$1.38 \textdegree{}C per SD). In leave-
> region-out cross-validation against LCZ4r, accuracy was comparable (RMSE differences within
> station-level bootstrap uncertainty in all three windows), while BRUCE produced predictions at
> every held-out station, including those where LCZ4r is masked, and preserved finer-scale spatial
> structure than LCZ4r's discrete zone classification. Applied to 241 primary care territories,
> BRUCE's posterior exceedance probabilities allowed 96 to be classified with high confidence
> (model-based classifications), whereas a constant-width interval derived from LCZ4r cross-
> validation errors supported confident classification of none. The framework offers a
> statistically principled, operationally viable basis for intra-urban heat monitoring in data-
> heterogeneous settings.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

