---
aliases: ["Improving and Expanding Video Editing Capabilities Without Videos"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.34941"
url: "http://arxiv.org/abs/2611.34941v1"
published: "2026-11-25T18:59:55Z"
ingested: "2026-11-26T16:21:38Z"
authors:
  - "Ji Xie"
  - "Yanhao Jia"
  - "Xiangpeng Yang"
  - "Martin Q. Ma"
  - "Sihan Xu"
  - "Erik Cambria"
  - "Louis-Philippe Morency"
---

# Improving and Expanding Video Editing Capabilities Without Videos

## Abstract

> Image editing models can follow a wide range of instructions, but video editing models still lag
> behind, limited in part by the difficulty of collecting paired source and edited videos. Is it
> possible to transfer advanced image editing capabilities to video editors without new paired
> videos? We introduce Image-to-Video Transfer (I2VT), which improves pretrained video editors and
> expands them to new editing tasks using an image editor. It enables efficient post-training with
> no architectural changes and no new videos, using only individual images. Our key idea is to let
> the video editor role-play as an image editor: it edits an image as a one-frame video, with the
> image editor guiding the video editor's predictions at each denoising step. Although the video
> editor sees only single images during training, at test time it applies the improved and
> expanded capabilities to whole video clips while preserving temporal consistency. To push the
> boundaries of video editing, we introduce OpenVE++, an extension of OpenVE-Bench that adds four
> new editing tasks useful for video production, including action changes, expression changes,
> body movements, and scene relighting. Our experiments across three different video editors show
> that I2VT improves existing editing capabilities and expands them to new tasks, and our models
> achieve state-of-the-art (SOTA) performance on both OpenVE-Bench and OpenVE++.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

