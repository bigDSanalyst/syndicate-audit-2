---
aliases: ["PathFM: Fast Generative Forecasting of Multivariate Trajectories"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.22358"
url: "http://arxiv.org/abs/2610.22358v1"
published: "2026-10-15T17:58:45Z"
ingested: "2026-10-16T10:40:12Z"
authors:
  - "Jiachen Yao"
  - "Xiyuan Zhang"
  - "Annan Yu"
  - "Boran Han"
  - "Abdul Fatir Ansari"
  - "Shuai Zhang"
  - "Michael Bohlke-Schneider"
  - "Bernie Wang"
---

# PathFM: Fast Generative Forecasting of Multivariate Trajectories

## Abstract

> Time series foundation models are becoming increasingly popular for general-purpose forecasting.
> However, most leading models predict marginal quantiles, leaving the dependence structure of
> future trajectories unspecified. This distinction matters for trajectory-dependent quantities
> such as cumulative demand, peak load, and event timing, yet point and marginal scores do not
> reveal it. To model this dependence, we introduce PathFM, a trajectory-based forecasting model
> that uses flow matching to generate complete future paths. We further distill the model to one
> or two steps and share history attention cache across draws. Together, these enable PathFM to
> generate multiple paths for a single series in roughly the time needed for one query to a
> quantile model. The distilled sampler also makes it practical to optimize a calibration loss
> directly. PathFM achieves competitive marginal accuracy on the established forecasting
> benchmarks fev-bench and TIME. To complement these evaluations, we introduce Forecast Path Score
> Bench (fps-bench), which augments fev-bench tasks with energy and variogram scores and
> downstream metrics. PathFM achieves a higher aggregate path score on fps-bench than all
> evaluated external baselines. Experiments on chaotic systems further show that our flow model
> sustains long-run variability, while strong baselines rapidly collapse. PathFM makes generative
> time series forecasting both competitive and practical, enabling diverse downstream
> applications.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

