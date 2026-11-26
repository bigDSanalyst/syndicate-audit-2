---
aliases: ["DynMF2: Rigid Motion Factorization by Expectation-Maximization for Monocular 4D Reconstruction and Motion Segmentation"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.34931"
url: "http://arxiv.org/abs/2611.34931v1"
published: "2026-11-25T18:59:14Z"
ingested: "2026-11-26T16:21:38Z"
authors:
  - "Agelos Kratimenos"
  - "Yile Hua"
  - "Kostas Daniilidis"
---

# DynMF2: Rigid Motion Factorization by Expectation-Maximization for Monocular 4D Reconstruction and Motion Segmentation

## Abstract

> A single casual video leaves a moving scene under-determined: a point seen once from each place
> can slide toward or away from the camera and still match every frame. We constrain the
> reconstruction with the structure of the motion itself. Building on DynMF, we model a scene's
> motion as a handful of SE(3) trajectories, each rigid, and let every point follow one of them
> alone, never a blend. DynMF2 computes this factorization directly from 3D point trajectories,
> with no rendering, by Expectation-Maximization (EM). Its M-step fits, in closed form, every
> rigid motion to the points assigned to it, and its E-step reassigns every point to the motion
> that explains it with the least error. The background is simply one more motion, the camera's,
> so no masks are needed. Three tools then revise the factorization: requery adds trajectories
> where the rendering shows parts the tracker missed, merge joins motions that move together, and
> split separates those that do not. Thus the number of motions follows the scene. Without masks,
> DynMF2 clearly outperforms the mask-based baselines in view synthesis on iPhone and NVIDIA and
> in 3D tracking on iPhone. It recovers what masks leave out, from thin parts and details to small
> movers far in the background. Its motions segment the moving parts of MOVi-F and iTACO scenes
> competitively, although DynMF2 is never trained to segment. What moves in a scene is not decided
> in advance: it emerges from the rigid motions themselves.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

