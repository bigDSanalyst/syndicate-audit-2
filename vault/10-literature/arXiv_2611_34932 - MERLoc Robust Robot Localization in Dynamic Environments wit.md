---
aliases: ["MERLoc: Robust Robot Localization in Dynamic Environments with Pose-Based Retrieval over 3D Gaussian Splatting References"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.34932"
url: "http://arxiv.org/abs/2611.34932v1"
published: "2026-11-25T18:59:23Z"
ingested: "2026-11-26T16:21:38Z"
authors:
  - "Michael Baumgartner"
  - "Dario Mylonopoulos"
  - "Sammy Christen"
  - "Markus Gross"
  - "Moritz Bacher"
---

# MERLoc: Robust Robot Localization in Dynamic Environments with Pose-Based Retrieval over 3D Gaussian Splatting References

## Abstract

> Robots operating in previously mapped spaces must localize accurately despite moving people and
> rearranged objects. Most localization pipelines match the query against a sparse set of captured
> reference images retrieved by appearance, which is brittle under scene change and repeating
> structures. We present MERLoc, which turns a single metric 3D Gaussian Splatting scan into a
> dense Functional Reference Memory. Reference views are sampled over the navigable space for the
> robot's morphology and sensors at a target density and rendered offline. Pre-encoding them for
> the chosen off-the-shelf localizer removes the reference encoder from inference. A pose-based
> retrieval strategy then selects references by spatial proximity and viewing direction rather
> than appearance, sidestepping visual ambiguities whenever a prior exists. Across one classical
> and four learned localizers in simulated and real dynamic scenes, pose-based retrieval matches
> or outperforms appearance retrieval in most cases, even when the latter is gated by the same
> prior. On real data, it lowers position RMSE by 15-60 % in nine of ten backend/split
> combinations, and the rendered memory outperforms real-image caches posed by Structure-from-
> Motion. The system runs onboard a Jetson Orin NX at 5 Hz, enabling a navigation policy to
> successfully traverse a hallway with people roaming and rearranging objects.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

