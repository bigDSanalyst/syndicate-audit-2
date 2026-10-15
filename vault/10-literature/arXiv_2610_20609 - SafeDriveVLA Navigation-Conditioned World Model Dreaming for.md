---
aliases: ["SafeDriveVLA: Navigation-Conditioned World Model Dreaming for Conflict-Aware End-to-End Autonomous Driving"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.20609"
url: "http://arxiv.org/abs/2610.20609v1"
published: "2026-10-14T17:59:56Z"
ingested: "2026-10-15T10:50:18Z"
authors:
  - "Shaoyuan Xie"
  - "Zihan Zhang"
  - "Jingxuan Wang"
  - "Jiashu Qu"
  - "Xiaoqing Liang"
  - "Lingdong Kong"
  - "Junchi Lu"
  - "Henrik I. Christensen"
  - "Qi Alfred Chen"
---

# SafeDriveVLA: Navigation-Conditioned World Model Dreaming for Conflict-Aware End-to-End Autonomous Driving

## Abstract

> Vision-Language-Action (VLA) models are gaining attention in autonomous driving, inheriting
> commonsense priors from large language models (LLMs) and widening the navigation interface from
> a fixed command set to free-form natural-language instructions. However, this open-ended
> interface exposes a new vulnerability surface: an inattentive driver may issue instructions that
> are unsafe given the current scene, and a malicious user may issue dangerous ones on purpose. We
> present the first benchmark suite that evaluates navigation following and conflict awareness
> together, along with adversarial robustness. Existing VLAs fall short on both: SimLingo
> completes no language-instructed lane change in closed loop, and all models degrade sharply
> under conflicting signals. We propose SafeDriveVLA, the first driving VLA that (1) explicitly
> predicts a three-level navigation-compliance mode to decouple conflict reasoning from action
> generation, and (2) uses navigation-conditioned world model dreaming to inform this prediction.
> Unlike prior world models that roll out expert or planned actions, ours dreams of strictly
> following the navigation signal, showing when following is safe. SafeDriveVLA reaches 88.16
> Driving Score (DS) and 68.64% Success Rate (SR) on Bench2Drive, lifts closed-loop language
> following by 49.3% and reduces collisions under unsafe instructions from 60 to 38 compared to
> the best SimLingo variant. Video demonstrations are available on our project page.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

