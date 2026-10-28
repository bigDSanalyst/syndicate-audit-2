---
aliases: ["Toward Circuit-Aware Mutation Testing for Quantum Programs: Exact Visibility and Execution Planning"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.36976"
url: "http://arxiv.org/abs/2610.36976v1"
published: "2026-10-27T10:31:07Z"
ingested: "2026-10-28T12:05:15Z"
authors:
  - "Andriy Miranskyy"
  - "Jose Campos"
---

# Toward Circuit-Aware Mutation Testing for Quantum Programs: Exact Visibility and Execution Planning

## Abstract

> Mutation testing assesses test suites by introducing program changes and checking whether tests
> detect them. In quantum programs, a surviving mutant may leave program behavior unchanged,
> produce a change hidden by the chosen input or measurement, or remain undetected because
> statistical evidence is insufficient. We develop a circuit-aware framework to distinguish these
> causes and guide execution planning and test changes. The framework covers ideal, noiseless
> programs and mutations that replace one gate or subcircuit. The method traces how a mutation can
> affect measured outputs and combines established mathematical checks with statistical estimates.
> For supported cases, we establish conditions under which a test cannot reveal a mutation and
> exact formulas for its effect when the required state information is available. Under stated
> assumptions, we bound the mutation score while retaining surviving and unresolved mutants, and
> identify a restricted circuit family whose mutation effects admit efficient classical
> classification. The deliverables include a decision procedure, mathematical guarantees, worked
> examples of test changes and their implementation requirements, and a small-circuit reference
> implementation for differential expectation tests. These results help testers decide what to
> execute, what to change, and what remains unknown. The evidence is limited to proofs and
> executable examples under the ideal model.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

