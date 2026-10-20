---
aliases: ["VideoMaMa++: Temporally Consistent Video Matting via Preserve-and-Refine Token"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.26857"
url: "http://arxiv.org/abs/2610.26857v1"
published: "2026-10-19T17:59:56Z"
ingested: "2026-10-20T10:54:56Z"
authors:
  - "Sangbeom Lim"
  - "Seoung Wug Oh"
  - "Heeji Yoon"
  - "Seungryong Kim"
  - "Joon-Young Lee"
---

# VideoMaMa++: Temporally Consistent Video Matting via Preserve-and-Refine Token

## Abstract

> Diffusion-based video matting has recently emerged as a leading approach, leveraging video
> diffusion priors from internet-scale pretraining to achieve strong zero-shot generalization from
> limited synthetic data. However, the heavy compute of these diffusion backbones limits inference
> to a short chunk of just 6 to 24 frames, so even ordinary videos span multiple chunks. Because
> each chunk is matted independently from coarse mask guidance, existing methods fail to maintain
> consistency across chunk boundaries, producing flickering edges and discontinuous transparency.
> We address this with a mask-guided diffusion-matting framework built on two ideas. The RGB and
> mask conditioning are represented as separate token streams that interact through full spatio-
> temporal self-attention, letting the model adaptively combine fine RGB texture with coarse mask
> layout rather than committing to a fixed channel-wise fusion. On top of this, we propose a novel
> pair of learnable embeddings, the preserve token and the refine token, that act as a per-frame
> conditioning interface and enable a sliding-window inference scheme in which already-generated
> mattes are propagated across chunk boundaries for local temporal consistency, complemented by a
> globally shared reference anchor at every chunk to prevent error accumulation in long sequences
> without any additional training. Across standard video matting benchmarks and in-the-wild long
> footage, our framework outperforms prior diffusion-based methods in both fine-detail accuracy
> and temporal consistency, and uniquely maintains consistency across chunk boundaries on long
> videos.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

