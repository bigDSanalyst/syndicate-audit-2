---
aliases: ["Images Talk Back: Guiding MMDiTs by Suppressing Image-to-Text Feedback"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.13941"
url: "http://arxiv.org/abs/2610.13941v1"
published: "2026-10-09T17:58:15Z"
ingested: "2026-10-12T14:23:25Z"
authors:
  - "Yucheng Yang"
  - "Xiaoxiao Sun"
  - "Shusheng Yang"
  - "Jiakang Chen"
  - "Serena Yeung-Levy"
---

# Images Talk Back: Guiding MMDiTs by Suppressing Image-to-Text Feedback

## Abstract

> Multimodal diffusion transformers (MMDiTs) allow the evolving image to update internal text
> representations through joint attention. These representations then guide subsequent image
> updates, raising a question: does this feedback help correct deviations from the prompt, or
> preserve them? We find that image-to-text (I2T) feedback can preserve the objects and attributes
> already represented in the evolving image, including errors. Transplanting I2T messages can
> rescue failures or disrupt successes. At matched intervention strengths, suppressing the
> influence of I2T feedback improves generation, whereas opposite controls degrade it. These
> findings motivate Semantic Feedback Guidance (SFG), which suppresses the influence of I2T
> feedback by guiding away from an auxiliary branch that strengthens this feedback and weakens
> text-to-image conditioning. The in-place variant, iSFG, directly suppresses I2T feedback and
> strengthens text-to-image conditioning, requiring no extra model evaluations. Temporal
> interventions motivate running the SFG branch during the first 20% of image sampling steps,
> requiring about $1.2\times$ the base NFE without classifier-free guidance (CFG). Experiments
> across three image-generation backbones show gains in alignment and preference-model scores. On
> FLUX, adding SFG to CFG raises GenEval from $0.6661$ to $0.7479$; on SD3.5M, iSFG adds $+1.33$
> HPSv2.1 over CFG at zero extra NFE. The control also transfers to text-to-video and image-to-
> video generation, improving VBench scores. Code is available at https://github.com/yyc1215lll-
> creator/SFG.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

