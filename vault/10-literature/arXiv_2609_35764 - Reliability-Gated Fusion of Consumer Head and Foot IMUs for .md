---
aliases: ["Reliability-Gated Fusion of Consumer Head and Foot IMUs for Lower-Body 3D Pose"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2609.35764"
url: "http://arxiv.org/abs/2609.35764v1"
published: "2026-09-28T17:59:22Z"
ingested: "2026-09-29T12:06:21Z"
authors:
  - "Zhilin Guo"
  - "Boqiao Zhang"
  - "Oszkár Urbán"
  - "Josef Bengtson"
  - "Hakan Aktas"
  - "Wenzhao Li"
  - "Siyu Hong"
  - "Kyle Fogarty"
  - "Chenliang Zhou"
  - "Ali Senguel"
  - "Cengiz Oztireli"
---

# Reliability-Gated Fusion of Consumer Head and Foot IMUs for Lower-Body 3D Pose

## Abstract

> Sparse inertial pose estimation promises camera-free motion capture from consumer devices, but
> consumer sensors are unreliable: firmware-fused orientations are biased, mounting varies between
> sessions, and streams drift or drop out. On a new 35-take single-subject benchmark pairing an
> earbud head inertial measurement unit (IMU) with two smart-insole foot IMUs (SAM-3D-Body pseudo-
> ground-truth labels), we show the reliability problem is channel-level: a channel ablation
> isolates foot acceleration as the most informative input (66.6 mm vs. 79.0 mm head-only) and the
> firmware-fused foot orientation as the liability that destroys the gain. We therefore let the
> model learn how much to trust each channel of each stream: one temporal gate per stream per
> channel block, trained with an auxiliary reliability objective on synthetically corrupted
> pretraining data. The channel-gated model is the most accurate of our learned fusion arms on
> clean data (69.4 mm vs. 83.7 static, 86.6 ungated) and under every simulated fault (bias in
> training; drift, dropout eval-only); its gates suppress the natively biased foot-orientation
> channels on clean real data without test-time supervision and flag dropout bursts at 0.92-0.999
> AUROC. Two contrasts: dropping a channel known a priori to fail is flat across foot faults but
> collapses when an unanticipated stream fails (head dropout: 92.9 vs. 79.3 mm); and a fine-tuned
> HMD-Poser is more accurate on clean data (64.4 mm) and nominally under drift, with no
> significant paired difference under bias or dropout, but a larger worst-case degradation from
> clean (+16.1 vs. +3.5 mm, single seed). Learning to gate reliability instead of sensor count is
> the lever for deployable sparse inertial capture. Code is available at
> https://github.com/ZhilinGuo/reliability-gated-imu-fusion.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

