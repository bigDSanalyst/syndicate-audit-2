---
aliases: ["Locating Contact on Tendon-Driven Continuum Robots From Tendon Measurements Alone via Constrained Moving Horizon Estimation"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.09877"
url: "http://arxiv.org/abs/2611.09877v1"
published: "2026-11-06T18:53:10Z"
ingested: "2026-11-09T15:08:07Z"
authors:
  - "Haitham El-Hussieny"
---

# Locating Contact on Tendon-Driven Continuum Robots From Tendon Measurements Alone via Constrained Moving Horizon Estimation

## Abstract

> Tendon-driven continuum robots can reach through constrained spaces, but contact along their
> bodies is invisible to the sensors at their motors. We show that this is a structural limitation
> rather than a tuning problem: the map from contact forces to tendon measurements has a null
> space of dimension at least seven, so no estimator that leaves the contact support free can
> locate contact. When the obstacle geometry is known, however, non-penetration and
> complementarity make the contact force locally identifiable, and we prove that the resulting
> system with unknown contact inputs is locally exponentially strongly detectable. We present a
> constrained moving horizon estimator (MHE) that encodes these conditions and runs in real time
> as one quadratic program per sample, and we give a local, mode-wise robust stability result for
> it. In a finite- element benchmark of a two-section robot pressing and sliding on a wall, the
> estimator located contact to 0.9 mm and estimated contact force to 0.22 N, compared with 65 mm
> and 0.72 N for a tuned extended Kalman filter (EKF) with state projection. The estimator
> tolerated millimeter- level errors in the obstacle position and unmodeled wall friction, under
> which the projected EKF failed. Under randomized model mismatch over 40 trials, including
> unmodeled tendon friction, it remained better in force and location in every trial. Without
> contact, the MHE offered no advantage over the EKF, which confirms that its benefit comes from
> the contact constraints. This report extends a letter submitted to IEEE Control Systems Letters
> with complete proofs and additional experiments.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

