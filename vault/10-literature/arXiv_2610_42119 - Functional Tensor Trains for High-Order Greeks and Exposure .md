---
aliases: ["Functional Tensor Trains for High-Order Greeks and Exposure Tails of Multi-Asset Structured Products"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.42119"
url: "http://arxiv.org/abs/2610.42119v1"
published: "2026-10-30T17:52:14Z"
ingested: "2026-11-02T14:43:34Z"
authors:
  - "Javier Lopez-Piqueres"
  - "Atithi Acharya"
  - "Yue Sun"
  - "Niraj Kumar"
---

# Functional Tensor Trains for High-Order Greeks and Exposure Tails of Multi-Asset Structured Products

## Abstract

> Risk management of worst-of autocallables needs price sensitivities (Greeks) up to third order
> and the potential future exposure, a tail quantile of the note's future value. In Monte Carlo,
> each order of differentiation multiplies the sampling noise by a factor that grows with the
> observation frequency, and nested simulation turns the noise of its inner paths into a bias of
> the quantile. We instead solve the backward pricing recursion, storing the continuation value as
> an $hp$ functional tensor train (hp-FTT) whose piecewise-polynomial cores are split at the
> barriers, so that worst-of barrier events act exactly, with rank one. For Gaussian transitions
> we show that the polynomial degree sufficient for an error $\varepsilon$ grows only as
> $\sqrt{\log(1/\varepsilon)}$. One solve then gives every Greek at any spot without sampling
> noise, by integrating the likelihood-ratio weight against the stored value, and the values it
> stores at future dates replace inner simulation. Against the strongest Monte Carlo estimators we
> could build or find published, on worst-of autocallables observed monthly on three to five
> assets, the order of the Greek and the accuracy decide which method is cheaper. At $1\%$
> accuracy Monte Carlo is more than an order of magnitude cheaper for deltas, second-order Greeks
> go either way, and hp-FTT is cheaper for every third-order Greek, by up to two orders of
> magnitude. At $0.1\%$ hp-FTT is cheaper for every Greek we could check, under geometric Brownian
> motion and local volatility alike. For the exposure alone Monte Carlo is cheaper at $1\%$ and
> hp-FTT at $0.1\%$, and a solve run for the Greeks yields it for little more than scenario
> sampling. Sampling pays in variance for each derivative and hp-FTT in rank for each asset, so
> Monte Carlo keeps low-order Greeks at percent accuracy, rarely observed contracts and many
> assets.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

