---
aliases: ["Secret-shared teleportation of a two-qudit gate with a deferred recipient"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.42150"
url: "http://arxiv.org/abs/2610.42150v1"
published: "2026-10-30T17:59:43Z"
ingested: "2026-11-02T14:43:38Z"
authors:
  - "Tanay Roy"
---

# Secret-shared teleportation of a two-qudit gate with a deferred recipient

## Abstract

> An unknown quantum operation, like an unknown quantum state, cannot be perfectly copied or
> stored for later use. A specific gate can be embedded in an entangled resource and teleported,
> but its destination is fixed when the resource is created. Here we show that the capability to
> apply a two-qudit entangling gate can instead be secret-shared among many parties: the shares
> are distributed in advance, and a later key release lets exactly one of them, chosen after
> distribution, exercise it. A provider encrypts half of a Bell pair held with a user into $n$
> shares, one per candidate node. The selected node, given the key qudits, completes an exact non-
> local $\mathtt{CSUM}^{k}$ gate with the user's data, in every measurement branch and for any
> qudit dimension, with the power $k$ chosen by the user alone. Any coalition of fewer than $n$
> candidate nodes, or the key register alone, holds no information, unselected nodes cannot tell
> whether a selection occurred, and the key cannot decrypt twice. For two candidates the registers
> form a $((3,5))$ threshold scheme. Encoder and decoder are explicit $O(n)$ circuits. The
> construction supports jointly authorized and anonymous gate application, advancing distributed
> quantum computing and quantum network capabilities.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

