---
aliases: ["Why Last-Iterate Scale-Invariant Regret Matching Converges Linearly?"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.38162"
url: "http://arxiv.org/abs/2609.38162v1"
published: "2026-09-29T17:59:18Z"
ingested: "2026-09-30T11:54:08Z"
authors:
  - "Boning Li"
  - "Longbo Huang"
---

# Why Last-Iterate Scale-Invariant Regret Matching Converges Linearly?

## Abstract

> IREG-PRM+ normalizes the cumulative regret vector by its own norm and attains optimal regret
> without knowledge of the payoff scale. Run unmodified on zero-sum matrix games, it converges
> linearly in the last iterate, and no analysis explains why. The obstacle is that the algorithm
> has no fixed step size to analyze: the step size is a state variable, the inverse of a regret
> norm that the trajectory itself moves. Every proved linear rate for regret-matching dynamics
> comes from restarting or modifying the update. We identify the mechanism as norm saturation: the
> regret norm rises to a finite limit and freezes the step size. We prove that it always does,
> with an explicit bound, and that saturation forces the last-iterate Nash gap to vanish on every
> matrix game; pointwise convergence follows whenever the equilibrium is unique. Near a unique
> strictly complementary equilibrium the active support freezes in one step, and the one-round
> Jacobian on that support has a closed form. The last-iterate then converges linearly at a
> closed-form rate, provided one scale-invariant quantity stays below one: the saturated step size
> times the largest singular value of the value-centered payoff submatrix on the support. On the
> $216$-instance testbed, the $184$ instances with a resolvable limit all satisfy it. The same
> analysis gives a ratio certificate: observable norm-increment ratios bound the unobservable
> Nash-gap ratio up to a constant that enters once and does not accumulate with the iteration
> count. Its slope-two law holds on $96.1\%$ of the instances where the slope is measurable, and
> the same increment monitors progress in extensive-form games, where best-response passes can be
> scheduled sparsely. The code is available at https://github.com/lbn187/NormCert.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

