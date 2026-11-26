---
aliases: ["Neural Network Decoders For Qubit Loss"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.34891"
url: "http://arxiv.org/abs/2611.34891v1"
published: "2026-11-25T18:47:12Z"
ingested: "2026-11-26T16:21:34Z"
authors:
  - "J. Wilson Staples"
  - "Winston Fu"
  - "Yihe Dong"
  - "Jeff D. Thompson"
---

# Neural Network Decoders For Qubit Loss

## Abstract

> Qubit loss is a significant source of error in many quantum hardware platforms, requiring
> circuits that periodically replace or reset qubits to maintain fault-tolerance. When the reset
> process includes loss-resolving measurements, this information can improve decoding and
> substantially reduce overhead compared to the case where this information is not available.
> Prior work has demonstrated loss-tolerant circuits for the surface code that show significantly
> improved thresholds and subthreshold scaling by incorporating loss information. However, the
> computational complexity of loss simulation and decoding, which falls outside of the usual
> stabilizer framework, has limited extending these studies to high-rate qLDPC codes, which are
> already challenging to decode in the absence of loss. In this work, we present a loss-aware
> convolutional neural-network (CNN) decoder framework that circumvents this challenge. Training
> is enabled by a novel sampler, \texttt{slim}, which achieves a throughput for circuits with
> Pauli noise and loss that is comparable to the state-of-the-art for pure Pauli noise. On the
> surface code with loss, the decoder matches the accuracy of computationally expensive most-
> likely error (MLE) decoders at much lower latency. For the $[[144,12,12]]$ bivariate bicycle
> (Gross) code, we study a walking syndrome extraction circuit with Pauli and loss errors. For
> physical error rates $p<1\%$, we observe a more than $10^3$-fold lower logical error rate for a
> pure loss model, relative to a pure Pauli error model at the same physical error rate, along
> with significantly enhanced sub-threshold error rate scaling. This demonstrates that loss-
> dominated error models can also significantly improve performance in a high-rate qLDPC code, and
> provides a simulation and decoder training platform that can be extended to other codes and
> algorithmic gadgets.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

