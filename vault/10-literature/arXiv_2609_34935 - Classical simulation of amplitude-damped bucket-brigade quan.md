---
aliases: ["Classical simulation of amplitude-damped bucket-brigade quantum random access memories via predictable branch evolution"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.34935"
url: "http://arxiv.org/abs/2609.34935v1"
published: "2026-09-28T11:32:18Z"
ingested: "2026-09-29T12:06:17Z"
authors:
  - "Zhao-Yun Chen"
  - "Ming-Yang Tan"
  - "Sheng Zhang"
  - "Peng Wang"
  - "Yun-Jie Wang"
  - "Guo-Ping Guo"
---

# Classical simulation of amplitude-damped bucket-brigade quantum random access memories via predictable branch evolution

## Abstract

> Classical simulation of quantum random access memory (QRAM) under noise can be accelerated
> dramatically by branch pruning: noise histories are sampled as trajectory ensembles, and good
> branches, whose routing paths avoid every sampled fault, need not be evolved because their final
> states are analytically predictable. Under amplitude damping this predictability is not
> automatic, because the no-jump operator $K_0$ acts on every branch at every time slice. Here we
> give a complete account of damping-channel predictability in bucket-brigade QRAM simulation, for
> both qutrit and qubit encodings. For the qutrit encoding, $K_0$ is diagonal in the node basis,
> and the wait state $|W\rangle$ is its fixed point, so a good branch follows the noiseless orbit
> up to a scalar attenuation. In the qubit encoding, phase-kickback memory fetching between two
> Hadamard walls makes $K_0$ no longer diagonal, yet the resulting structure is exactly solvable
> in closed form. Conditional on no jump, the in-branch infidelity of a good branch is second
> order in the damping rate $γ$, with coherent leakage $\sim n^2γ^2/4$ per data qubit, and the
> closed form captures it without approximation. We also revise the pruning criterion for the
> qubit encoding. The resulting algorithm evolves only the bad branches plus one reference branch
> and shares every other cost with the full evolution it replaces. It is validated by end-to-end
> benchmarks with pruned-over-full speedups up to $285\times$ and by trajectory-level tests
> confirming every closed form to machine precision.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

