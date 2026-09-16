---
aliases: ["Verifiable Social Reasoning for LLM Assistants"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.17496"
url: "http://arxiv.org/abs/2609.17496v1"
published: "2026-09-15T17:37:29Z"
ingested: "2026-09-16T10:49:46Z"
authors:
  - "Amir Taubenfeld"
  - "Zorik Gekhman"
  - "Avigail Grinstein-Dabush"
  - "Itay Laish"
  - "Ariel Goldstein"
  - "Marian Croak"
  - "Avinatan Hassidim"
  - "Yossi Matias"
  - "Amir Feder"
---

# Verifiable Social Reasoning for LLM Assistants

## Abstract

> LLM assistants are widely used for daily social advice, yet evaluating their social reasoning in
> such consultation settings remains challenging since (i) it requires setups where the assistant
> learns about social situations from subjective user narratives, and (ii) social properties, such
> as others' intentions, typically lack verifiable ground truth. To address these challenges, we
> introduce Fuse, a multi-agent simulation framework for studying user-mediated social reasoning.
> In Fuse, a target agent with a hidden motive interacts with other agents including one
> representing the user, who then consults the evaluated assistant to infer the target's motive,
> providing verifiable ground truth by construction. Simulation faithfulness is validated through
> a human study with 24k annotations. We apply Fuse to 12 LLMs and demonstrate its analytical
> utility by systematically isolating key factors, showing that (i) user mediation compounds the
> inherent difficulty of social reasoning; (ii) LLMs exhibit systematic sensitivity to biased user
> framing; (iii) models can require more details than humans need to reach a correct prediction;
> and (iv) longer conversations do not always improve performance despite providing opportunities
> for clarifying questions. We open-source Fuse and a dataset with 21k examples.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

