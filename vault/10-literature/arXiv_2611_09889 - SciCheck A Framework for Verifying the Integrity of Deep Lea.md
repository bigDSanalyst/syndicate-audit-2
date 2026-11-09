---
aliases: ["SciCheck: A Framework for Verifying the Integrity of Deep Learning Training"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.09889"
url: "http://arxiv.org/abs/2611.09889v1"
published: "2026-11-06T18:58:38Z"
ingested: "2026-11-09T15:08:07Z"
authors:
  - "Alexander Nguyen"
  - "Dylan Gresham"
  - "Gaby G. Dagher"
  - "Min Long"
---

# SciCheck: A Framework for Verifying the Integrity of Deep Learning Training

## Abstract

> Deep learning training is difficult to verify within a scientific workflow: its architecture,
> hyperparameters, and procedure are rarely fixed until training has been attempted, and two
> honest runs never produce the same weights, so recomputation cannot serve as a check. We present
> SciCheck, a framework in which the scientist explores training configurations freely and posts a
> blueprint to a provenance ledger for each candidate they want verified, and a verifying
> scientist judges the resulting run in two layers: a statistical judge model that compares per-
> step gradient statistics against the verifier's own reference run, and a spot-check that re-
> executes randomly chosen training segments whose checkpoints are committed to the ledger one
> epoch at a time. On an MLP, a CNN, and an autoencoder at 100k-500k parameters, under gradient
> sign flipping, label poisoning, and fabricated runs, SciCheck reaches F1 of 0.966, 0.906, and
> 0.976 while rejecting 0-4.4% of honest runs. For the attacks we test, the spot-check accounts
> for most of this accuracy, and we characterize what each layer can detect. The effective-signal
> statistic falls as $(1-2s)^2$ under a sign flip of severity $s$, so gradient statistics alone
> catch strong enough sign flips, while fabricated runs that replay genuine statistics look no
> more anomalous than honest runs to any statistical detector we test. The spot-check catches
> fully fabricated segments with probability at least $1-(1-s)^k$ for $k$ sampled segments when
> the draws stay hidden until the run is committed, which roughly matches our measurements and
> lets a verifier choose $k$ for a target soundness. Verification costs 1.5-2.3x one retraining,
> mostly for the verifier's reference run; each submission's spot-check takes under 1.5 s, and
> per-epoch commitments reduce checkpoint storage 5-17x compared with keeping every checkpoint.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

