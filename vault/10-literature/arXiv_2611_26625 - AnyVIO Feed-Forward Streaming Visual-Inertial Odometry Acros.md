---
aliases: ["AnyVIO: Feed-Forward Streaming Visual-Inertial Odometry Across Platforms"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.26625"
url: "http://arxiv.org/abs/2611.26625v1"
published: "2026-11-19T18:59:35Z"
ingested: "2026-11-20T14:52:15Z"
authors:
  - "Omoruyi Atekha"
  - "Marcus Greiff"
  - "Ray Zhang"
  - "Luca Carlone"
---

# AnyVIO: Feed-Forward Streaming Visual-Inertial Odometry Across Platforms

## Abstract

> Geometric foundation models (GFMs) estimate camera mo- tion and scene structure from images
> without requiring ex- pert parameter tuning, but either lack metric scale or rely on learned
> priors to infer scale, which is unobservable from monocular images alone. Inertial sensing
> offers a way to observe metric scale, but existing methods add inertial in- formation through a
> filter or factor graph, which reintro- duces bespoke parameter tuning and optimization costs
> that can grow with the trajectory. To bridge this gap, we present AnyVIO, a real-time, feed-
> forward streaming model for monocular visual-inertial odometry (VIO), which combines a streaming
> GFM with an inertial foundation model (IFM). Both the GFM and IFM predict the metric motion
> between consecutive frames, and a lightweight learned fusion head quantifies the reliability of
> each estimate and blends them in a single forward pass. Across nine datasets recorded from cars,
> legged and ground robots, and handheld and head- mounted devices, AnyVIO reduces the metric
> position error of its visual model by 36% while publishing each pose esti- mate 70 ms after an
> image is received. We further deploy AnyVIO onboard two real vehicles at up to 140 km/h, where
> it remains accurate in poor lighting and heavy dust.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

