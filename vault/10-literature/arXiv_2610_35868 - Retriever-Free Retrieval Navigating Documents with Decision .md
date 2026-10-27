---
aliases: ["Retriever-Free Retrieval: Navigating Documents with Decision Models"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.35868"
url: "http://arxiv.org/abs/2610.35868v1"
published: "2026-10-26T17:59:44Z"
ingested: "2026-10-27T11:35:02Z"
authors:
  - "Chao Wan"
  - "Paul Jünger"
  - "Beixi Du"
  - "Bodong Liu"
  - "Navaneetha Krishnan"
  - "Kilian Q. Weinberger"
---

# Retriever-Free Retrieval: Navigating Documents with Decision Models

## Abstract

> While language models have become dramatically more capable, retrieval still largely relies on
> lexical matching or similarity in fixed embedding spaces. This creates a capability asymmetry:
> what the retriever fails to find, even the strongest generator cannot recover. We propose
> DecisionRAG, which brings the capabilities of pretrained language models to retrieval using
> decision models that jointly evaluate candidate branches in a single forward pass, without
> generating any tokens, and show that judging candidates in a shared context makes their
> relevance estimates comparable. Like a person browsing a library, DecisionRAG navigates the
> corpus's inherent structure from broad topics down to individual passages, deciding at each
> level which branches are worth exploring. Without task-specific training or a first-stage
> retriever, DecisionRAG outperforms dense retrieval with an 8B reranker by 13.8 R@1 points on
> MultiDoc2Dial and 17.4 Hit@1 points on Natural Questions. Across four benchmarks, including a
> corpus of 2.68 million Wikipedia paragraphs, retrieval takes just 0.7-1.8 seconds per query.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

