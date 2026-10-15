---
aliases: ["Representation Conditioning for Generation"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.20608"
url: "http://arxiv.org/abs/2610.20608v1"
published: "2026-10-14T17:59:52Z"
ingested: "2026-10-15T10:50:18Z"
authors:
  - "Saeed Razavi"
  - "Xingjian Leng"
  - "Liang Zheng"
---

# Representation Conditioning for Generation

## Abstract

> Representation-alignment methods effectively accelerate the diffusion transformer training.
> REPA, for example, uses a pretrained vision encoder to supervise an intermediate layer through
> an MLP projection head which is discarded after training. It aims to import semantics from the
> vision encoder to the diffusion backbone. While this objective is achieved at early layers by
> back-propagating the alignment loss, there is no guarantee that later layers, supervised by the
> velocity prediction loss alone, can well access such semantics. We propose a simple solution,
> representation conditioning (RECON), to improve semantics in later layers. During training, we
> feed the pretrained vision encoder tokens into later layers; during inference, because we no
> longer have the clean image, we reuse the MLP head (as a proxy to the vision encoder) and
> project its output tokens to the later layers. Our method adds no parameters and leads to much
> faster convergence: RECON is $63\times$ faster than SiT and $25\times$ faster than REPA. Code is
> available at https://github.com/saeidrazavi/RECON

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

