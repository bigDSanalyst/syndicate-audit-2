---
aliases: ["When Should We Intervene at Test Time?"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.37658"
url: "http://arxiv.org/abs/2610.37658v1"
published: "2026-10-27T17:58:53Z"
ingested: "2026-10-28T12:05:19Z"
authors:
  - "Jiahao Zhang"
  - "Xinling Wen"
  - "Liangliang Li"
  - "Yu Chen"
---

# When Should We Intervene at Test Time?

## Abstract

> Test-time adaptation helps a deployed model respond to changing inputs, but the same
> intervention can rescue one batch and damage the next. Updating normalization statistics, for
> example, can improve corrupted images yet fail when a batch contains mostly one class. Average
> accuracy hides these failures and cannot tell a model when to use an intervention. Target labels
> can guide this decision, but they are scarce and some choices are already clear. We introduce
> PORTAL, a controller that chooses when to deploy an intervention, which inputs to label, and
> when to stop querying. Each available prediction rule is a candidate, and its predictions are
> fixed before current feedback arrives. Every acquired label therefore evaluates all candidates
> on the same input. PORTAL combines these shared comparisons and directs queries toward
> candidates that can still overtake the current leader. It stops when the remaining labels cannot
> change the choice or when the possible accuracy gain no longer justifies another query. Our
> analysis links the required feedback to accuracy gaps and shared mistakes, explaining why some
> choices need much less evidence. Experiments show that this control turns an intervention that
> loses accuracy overall into a useful choice on selected batches. It prevents severe failures
> caused by changes in arrival order and preserves gains across complete corruption streams. When
> a fixed rule already works well, PORTAL uses little feedback to retain its performance. Periodic
> label checks reveal when past evidence needs refreshing and help the controller recover as
> conditions change. The acquired labels also train stronger candidates for future batches, and
> selection brings nearly all of their accuracy gains into deployment. The same feedback therefore
> improves both the choice made now and the predictions available to later batches.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

