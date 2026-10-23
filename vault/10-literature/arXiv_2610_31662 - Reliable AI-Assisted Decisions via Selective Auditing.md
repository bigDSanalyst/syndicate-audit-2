---
aliases: ["Reliable AI-Assisted Decisions via Selective Auditing"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.31662"
url: "http://arxiv.org/abs/2610.31662v1"
published: "2026-10-22T17:59:22Z"
ingested: "2026-10-23T10:59:11Z"
authors:
  - "Isaac Gibbs"
  - "Elise L. Han"
  - "Ryan J. Tibshirani"
  - "Tijana Zrnic"
---

# Reliable AI-Assisted Decisions via Selective Auditing

## Abstract

> We consider online monitoring of an AI system that produces a sequence of decisions. At each
> round, the system outputs a proposed decision together with a confidence score estimating the
> trustworthiness of the decision. The decision and confidence score need not be produced by the
> same model: for example, one agent may propose a decision, while a separate verifier agent
> evaluates it and outputs a correctness or safety score. Based on this information, we must
> decide whether to accept the AI decision automatically or consult an expert, such as a human
> auditor, who reviews the proposal and either accepts or corrects it. We formulate this task as
> an online constrained optimization problem in which the goal is to minimize the frequency of
> expert auditing while guaranteeing that the fraction of AI errors that go unaudited stays below
> a user-defined threshold. We derive a family of algorithms with provable error-control
> guarantees with no assumptions, including a method that is optimally efficient: it
> asymptotically attains the best achievable auditing rate for both adversarial and i.i.d. data
> streams. Experiments on screening harmful requests to large language models, qualitative text
> annotation, and data labeling show that our methods achieve valid error control in practice
> while substantially reducing the need for human auditing compared to baselines.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

