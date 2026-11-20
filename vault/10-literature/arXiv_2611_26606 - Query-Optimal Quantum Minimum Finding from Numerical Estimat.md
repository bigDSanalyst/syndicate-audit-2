---
aliases: ["Query-Optimal Quantum Minimum Finding from Numerical Estimators"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.26606"
url: "http://arxiv.org/abs/2611.26606v1"
published: "2026-11-19T18:55:55Z"
ingested: "2026-11-20T14:52:15Z"
authors:
  - "Egil Bae"
---

# Query-Optimal Quantum Minimum Finding from Numerical Estimators

## Abstract

> We propose a quantum minimum-finding algorithm for objectives accessed via numerical estimators
> that avoids the logarithmic query overhead of amplifying the confidence of estimates before the
> search. A coherent estimator that is $\varepsilon$-accurate with probability at least $2/3$ on
> each of $N$ labels suffices to find a $2\varepsilon$-optimal label using $O(\sqrt N)$ base-
> estimator queries at constant confidence. The query bound and the additive-error constant are
> separately worst-case optimal. More generally, suppose a preparation assigns probability mass at
> least a known $p$ to objective values at most $a$. Without knowing $a$ or the prepared
> distribution, our algorithm returns a candidate and an estimate $v$ such that, jointly with
> constant probability, $v$ is $\varepsilon$-accurate for the candidate and $v\le a+\varepsilon$.
> The algorithm uses $O(p^{-1/2})$ queries to each of the preparation and estimator oracles in the
> worst case, and the selected candidate can be retained as a quantum state. For preparation width
> $s_P$ and estimator workspace width $w$, it requires $O(s_P+w+\log\log(4/p))$ qubits,
> independently of the requested confidence. Applications give worst-case optimal $Θ(\sqrt N/η)$
> queries for selecting an $η$-optimal bounded expectation, and guided ground-energy estimation
> using $O(ω^{-1})$ preparations and $O((ωη)^{-1})$ elementary controlled-evolution queries at
> constant confidence, where $ω$ is a lower bound on the guiding state's ground-space amplitude
> overlap.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

