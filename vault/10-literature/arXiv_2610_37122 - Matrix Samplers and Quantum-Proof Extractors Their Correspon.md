---
aliases: ["Matrix Samplers and Quantum-Proof Extractors: Their Correspondence and Almost-Optimal Constructions"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.37122"
url: "http://arxiv.org/abs/2610.37122v1"
published: "2026-10-27T12:21:47Z"
ingested: "2026-10-28T12:05:15Z"
authors:
  - "Kuan Cheng"
  - "Ruiyang Wu"
---

# Matrix Samplers and Quantum-Proof Extractors: Their Correspondence and Almost-Optimal Constructions

## Abstract

> We establish an equivalence between matrix samplers and quantum-proof randomness extractors. The
> classical sampler--extractor equivalence is established by a seminal work of Zuckerman (Random
> Structures & Algorithms, 1997). Using this equivalence, we construct explicit strong matrix
> samplers with optimal randomness overhead and near-optimal sample complexity via constructing
> quantum-proof extractors. Specifically for matrix dimension $D$, accuracy $\varepsilon$ and
> failure probability $δ\leq\varepsilon$, our matrix sampler uses $m+O_α(\log(D/δ))$ random bits
> and $O_α(\varepsilon^{-2-α}\log^{1+α}(D/δ))$ samples, for any constant $α>0$. Compared with the
> matrix sampler of Xun and Zuckerman (CCC 2025), our construction has improvements in two
> aspects. Under the same optimal random seed length, we can replace the $\operatorname{poly} D$
> dependence in the number of samples by $O(\log^{1-γ} D)$. Under the same scale of sample size,
> we can remove their $\log\log D$ factor in the length of the random seed. Our underlying strong
> quantum-proof extractor has output length $n-O_α(a+\log(1/η))$ and seed length at most
> $(1+α)\log a+(2+α)\log(1/η)+O_α(1)$ for $n$-bit sources with conditional min-entropy $n-a$ and
> error $η$. We also obtain strong quantum-proof extractors for every constant entropy rate, for
> any error as small as $2^{-Ω(n)}$, having optimal seed length $O(\log(n/η))$ and output length
> $Ω(n)$, improving previous constructions.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

