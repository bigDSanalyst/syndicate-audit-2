---
aliases: ["Propose-Filter-Release: Scaling Noise to Typical Sensitivity via Private Filtering"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.40654"
url: "http://arxiv.org/abs/2610.40654v1"
published: "2026-10-29T17:59:49Z"
ingested: "2026-10-30T12:06:53Z"
authors:
  - "Moshe Shenfeld"
  - "Eliad Tsfadia"
  - "Katrina Ligett"
---

# Propose-Filter-Release: Scaling Noise to Typical Sensitivity via Private Filtering

## Abstract

> An estimator can be accurate and stable on typical data, yet sensitive to a few possible
> records. Differentially private mechanisms commonly scale their noise to the worst-case
> influence of a single record, which lets these records dictate the noise even when the remaining
> data would allow far less. Removing them first would restore the smaller scale, but the removal
> must itself be private. We introduce \emph{propose-filter-release} (PFR), which, by privately
> filtering its input, turns a mechanism that protects the addition or removal of a typical
> record, one that fits the remaining data, into one that is differentially private in the
> standard sense, on every input. Using our novel filtering step, PFR requires only a concave
> friendliness score, which measures how well a record fits a dataset, and a release mechanism
> that is friendly-DP, that is, private when the changed record fits the remaining data. For every
> such score and release mechanism, it guarantees differential privacy under public conditions on
> the number of records, so it is a general privacy primitive, comparable to propose-test-release,
> and FriendlyCore can be viewed as one of its implementations. We illustrate the generality of
> PFR by instantiating it for scalar statistics, principal subspace estimation, the KL divergence
> of user histograms, the effective resistances of a graph, and treatment-rule selection.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

