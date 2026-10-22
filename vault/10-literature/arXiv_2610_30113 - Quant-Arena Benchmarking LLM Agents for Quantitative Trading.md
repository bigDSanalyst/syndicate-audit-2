---
aliases: ["Quant-Arena: Benchmarking LLM Agents for Quantitative Trading Research"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.30113"
url: "http://arxiv.org/abs/2610.30113v1"
published: "2026-10-21T17:54:01Z"
ingested: "2026-10-22T11:08:02Z"
authors:
  - "Houde Qian"
  - "Zheng Jiang"
  - "Wenyi Li"
  - "Chenxi Xu"
  - "Xinjie Lin"
  - "Yuzhao Peng"
  - "Ruoyu Han"
  - "Youjie Zheng"
  - "Kaisen Yang"
  - "Qinhuai Na"
  - "You Fu"
  - "Calvin Xiao"
---

# Quant-Arena: Benchmarking LLM Agents for Quantitative Trading Research

## Abstract

> Quantitative research is an iterative loop: a researcher proposes a market hypothesis,
> implements it as an executable signal, tests it on historical data, and decides what to keep.
> Existing benchmarks score formulas, code, or individual trading decisions, leaving open whether
> large language models (LLMs) can complete this loop and produce strategies that work beyond the
> research period. We introduce Quant-Arena, a benchmark and public leaderboard for end-to-end
> quantitative research on real A-share market data. A model constructs features and stock-scoring
> code, receives feedback only on 2022--2023, and freezes one strategy for assessment on the
> sealed year 2024. A cash-account evaluator applies trading constraints and costs, including
> market impact estimated from a simulated order book. Scores are dominated by realized excess
> return and complemented by signal quality and the diversity of features used by the strategy. We
> evaluate nine frontier models, among which GPT-6 Astra scores highest; yet no model beats the
> equal-weight market in 2024. Quant-Arena is open to submissions from any model or agent harness.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

