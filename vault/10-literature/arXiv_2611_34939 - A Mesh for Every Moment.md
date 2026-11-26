---
aliases: ["A Mesh for Every Moment"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.34939"
url: "http://arxiv.org/abs/2611.34939v1"
published: "2026-11-25T18:59:45Z"
ingested: "2026-11-26T16:21:38Z"
authors:
  - "Roy Or-El"
  - "Jeong Joon Park"
  - "Ira Kemelmacher-Shlizerman"
---

# A Mesh for Every Moment

## Abstract

> We present MEMO (a Mesh for Every MOment), a method that reconstructs the geometry of complete
> dynamic scenes, captured by multiple synchronized cameras, and extracts a mesh at every frame.
> Existing dynamic Gaussian splatting methods either model appearance alone or target isolated
> objects segmented by foreground masks, and all of them recover meshes by TSDF fusion or Poisson
> reconstruction, whose fixed grids limit the detail they can capture. At the core of MEMO is a
> per-Gaussian motion model inspired by Gaussian processes, which represents each Gaussian's
> position and rotation over time as a combination of temporal Gaussian kernels. The model keeps
> every Gaussian a valid surface element throughout the sequence and carries an implicit
> representation of the dynamic geometry, so a mesh can be derived at any time from a field
> defined by the Gaussians. Although common in real captures, large and fast motion poses a
> challenge that dynamic Gaussian splatting methods usually overlook. To account for it, we design
> a track-based initialization scheme that fits each Gaussian's initial trajectory to point tracks
> in closed form. We evaluate MEMO on Blender-Moments, a new benchmark of nine animated scenes
> with ground-truth meshes at every frame, and on two real-world datasets. MEMO reconstructs the
> most accurate geometry among state-of-the-art methods, and remains competitive in novel-view
> synthesis and training time. Project page: https://memo-4d.github.io

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

