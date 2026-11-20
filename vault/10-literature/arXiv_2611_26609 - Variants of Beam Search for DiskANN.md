---
aliases: ["Variants of Beam Search for DiskANN"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.26609"
url: "http://arxiv.org/abs/2611.26609v1"
published: "2026-11-19T18:57:05Z"
ingested: "2026-11-20T14:52:15Z"
authors:
  - "Viraj Agrawal"
  - "Kirankumar Shiragur"
---

# Variants of Beam Search for DiskANN

## Abstract

> Graph-based data structures such as DiskANN, HNSW, and NSG constitute the state of the art for
> large-scale approximate nearest-neighbor (ANN) search. Indyk and Xu introduced the notion of
> $α$-reachable graphs, which include graphs built by DiskANN's slow-preprocessing construction,
> and proved that greedy search achieves an approximation factor of $\tfrac{α+1}{α-1}$.
> Independently, Al-Jazzazi et al. proposed adaptive beam search (ABS) with a relaxation parameter
> $γ> 0$, showing a $\tfrac{2}γ$ approximation on navigable graphs ($α\approx 1$), where greedy
> search admits no guarantees. In this work, we unify and generalize these results by proving that
> ABS with parameter $γ$ on $α$-reachable graphs achieves an approximation of
> $\tfrac{α+1}{α(γ+1)-1}$ for any metric. Moreover, on sorted $α$-reachable graphs (introduced by
> Gollapudi et al.) under the $\ell_2$ metric, we obtain the tighter bound
> $\max\bigl(\tfracα{α(γ+1)-1}, \tfrac{α^{2}+1}{α^{2}(γ+1)-1}\bigr)$. Beyond these theoretical
> results, we design a beam predictor using features inspired by fine-grained analysis of ABS,
> trained via a constrained objective that minimizes mean distance computations subject to a
> target recall. On three 100-million-point benchmarks, using graphs built by DiskANN's practical
> construction, beam predictor lowers mean query latency on SSD-resident indices at matched recall
> by up to $29.6\%$ relative to classical beam search (CBS). Relative to ABS, it is faster in $11$
> of $15$ settings, by up to $6.5\%$, and at most $1.4\%$ slower in the other $4$; at $95\%$
> recall, its advantage over ABS grows from $0.8$--$4.2\%$ for $100$ neighbors to $4.6$--$5.6\%$
> for $500$ neighbors. In memory, it needs $1.3$--$23.7\%$ fewer distance computations than CBS
> and $0.0$--$3.9\%$ fewer than ABS.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

