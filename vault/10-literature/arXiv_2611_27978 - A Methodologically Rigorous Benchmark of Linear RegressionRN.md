---
aliases: ["A Methodologically Rigorous Benchmark of Linear Regression,RNN, and LSTM for S&P 500 Forecasting:Identifying Sources of Performance Inflation in Financial DeepLearning"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.27978"
url: "http://arxiv.org/abs/2611.27978v1"
published: "2026-11-20T18:57:15Z"
ingested: "2026-11-23T17:21:05Z"
authors:
  - "Hari Sitaula"
  - "Joseph Opitz"
---

# A Methodologically Rigorous Benchmark of Linear Regression,RNN, and LSTM for S&P 500 Forecasting:Identifying Sources of Performance Inflation in Financial DeepLearning

## Abstract

> This study examines one-day-ahead forecasting of the S&P 500 closing level using a 2006-2025
> dataset that includes fundamental price data, macroeconomic indicators, and engineered technical
> features. We benchmark three model families, namely linear regression, vanilla recurrent neural
> networks (RNN), and long short-term memory networks (LSTM), within a unified preprocessing and
> chronological evaluation pipeline. A central contribution of this work is a methodological audit
> of common practices in the deep-learning-for-stock-prediction literature. We identify three
> sources of result inflation that frequently appear in published methodologies: wavelet-denoised
> evaluation targets, the absence of a naive persistence baseline, and best-of-N replicate
> reporting. We then re-evaluate all model families under a corrected protocol that controls for
> each. Performance is reported using root mean squared error, mean absolute percentage error, and
> the Pearson correlation coefficient, averaged across N = 30 independent replicates per
> configuration. We compare models on accuracy, stability across replicates, and architectural
> depth sensitivity, using the naive persistence forecast (predicting today's close as tomorrow's
> close) as a primary baseline against which all candidate models must demonstrate improvement.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

