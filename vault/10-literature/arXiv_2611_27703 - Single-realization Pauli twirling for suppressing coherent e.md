---
aliases: ["Single-realization Pauli twirling for suppressing coherent error accumulation in structured quantum circuits"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.27703"
url: "http://arxiv.org/abs/2611.27703v1"
published: "2026-11-20T15:08:40Z"
ingested: "2026-11-23T17:21:01Z"
authors:
  - "Dihang Sun"
  - "Tianqi Chen"
  - "Jin Ming Koh"
  - "Nannan Ma"
  - "Jiangbin Gong"
---

# Single-realization Pauli twirling for suppressing coherent error accumulation in structured quantum circuits

## Abstract

> Pauli twirling is conventionally understood as an ensemble-level noise-tailoring procedure which
> suppresses coherent components of the error channel by averaging over randomized compilations.
> This picture does not by itself determine whether a single realization of Pauli-dressed circuit
> can outperform its bare counterpart, nor does it predict when such an advantage should occur. In
> this work, we present single-realization based framework for the standard Pauli dressing of two-
> qubit Clifford gates in structured quantum circuits. This is afforded by the key insight that
> for weak coherent errors, the leading gate infidelity is governed by the variance of some
> accumulated error generator. Through both simulations and theoretical considerations, we verify
> that coherent errors accumulated at different entangling gates can produce $Θ(L^2)$ variance
> growth in a bare circuit, whereas independent Pauli dressing eliminates the cross-layer
> contribution on average and yields an $O(L)$ variance bound at any fixed confidence level for a
> single randomly sampled realization. We then develop a covariance diagnostic that predicts when
> this mechanism is effective in error mitigation. We find a strong Pauli twirling advantage for
> coherent errors whose transported generators have large off-diagonal covariance, and little
> advantage when the covariance matrix is nearly diagonal. Hardware experiments on IBM
> superconducting processors demonstrate fidelity improvements for GHZ-state preparation and
> reduced observable errors in Trotterized transverse-field Ising dynamics. These results indicate
> that single realizations of Pauli twirling without ensemble averaging is a useful coherent-error
> suppression technique for structured circuits containing repeated nontrivial two-qubit
> operations.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

