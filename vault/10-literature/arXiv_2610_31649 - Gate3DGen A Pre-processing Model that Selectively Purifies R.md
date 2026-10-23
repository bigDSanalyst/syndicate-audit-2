---
aliases: ["Gate3DGen: A Pre-processing Model that Selectively Purifies Real-World Images for 3D Generation"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.31649"
url: "http://arxiv.org/abs/2610.31649v1"
published: "2026-10-22T17:57:02Z"
ingested: "2026-10-23T10:59:11Z"
authors:
  - "Xiaolin Li"
  - "Zihao Huang"
  - "Fanpeng Meng"
  - "Chen Yang"
  - "Guanjun Wu"
  - "Kai Zhang"
  - "Jiemin Fang"
  - "Qi Tian"
---

# Gate3DGen: A Pre-processing Model that Selectively Purifies Real-World Images for 3D Generation

## Abstract

> Single-image 3D generation has achieved high fidelity on curated benchmarks, yet degrades
> sharply on real-world images with uneven illumination, blur, and occlusions. Purifying such
> inputs requires deciding when to intervene and preserving the visual cues needed for 3D
> generation, while leaving clean inputs unchanged. We introduce Gate3DGen, a selective pre-
> processing model that gates image inputs to existing 3D generators without retraining them. A
> degradation-aware router bypasses inputs classified as clean and extracts features to guide
> purification of the remaining inputs. Conditioned on these features, a 3D-oriented one-step
> purifier purifies degraded inputs with spatial losses that encourage preservation of object
> identity, contours, and textural cues. To provide paired supervision, we construct a synthetic
> data engine that renders clean views of 3D assets and synthesises composite degradations. On the
> synthetic benchmark, the purifier improves image fidelity and downstream 3D geometry in only
> 2.3s on average, reducing TRELLIS.2 mesh distance by 61.5% relative to degraded inputs. VLM
> evaluation and human preferences on real photographs further support identity preservation and
> degradation correction. More demos and code are available at
> https://supra-3d.github.io/gate3dgen.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

