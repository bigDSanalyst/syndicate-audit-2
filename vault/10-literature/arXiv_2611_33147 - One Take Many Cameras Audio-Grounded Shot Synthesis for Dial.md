---
aliases: ["One Take, Many Cameras: Audio-Grounded Shot Synthesis for Dialogue Re-Cinematography"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2611.33147"
url: "http://arxiv.org/abs/2611.33147v1"
published: "2026-11-24T18:58:32Z"
ingested: "2026-11-25T16:45:53Z"
authors:
  - "Anthony Chen"
  - "Naomi Ken Korem"
  - "Matan Ben-Yosef"
  - "Tavi Halperin"
  - "Urska Jelercic"
  - "Ofir Bibi"
  - "Daniel Cohen-Or"
  - "Or Patashnik"
  - "Maneesh Agrawala"
---

# One Take, Many Cameras: Audio-Grounded Shot Synthesis for Dialogue Re-Cinematography

## Abstract

> Creating a dialogue scene typically requires cutting between multiple views (e.g., close-ups,
> medium shots, and over-the-shoulder shots) of the actors. Yet capturing such coverage is costly
> and in many settings unavailable. We study dialogue re-cinematography: synthesizing additional
> shots from a single wide-angle dialogue video. Existing video generators can synthesize new
> shots, but rely on visual cues alone, so when the source video barely shows the lips, the
> generated lip motion fails to match the speech. Our key observation is that the speech audio is
> view-invariant: it constrains lip motion in any target view. Building on this insight, we adapt
> a pretrained audio-visual diffusion model to generate the new shot from a target frame that
> specifies the view, a source video that contains the performance, and the speech audio that
> drives lip motion. In multi-person scenes, however, pretrained audio-visual models drive every
> visible face with the same speech, causing speech leakage, where silent listeners mouth the
> speaker's words. We therefore introduce speaker-aware audio gating, a training-free module that
> lets the audio drive only the faces that speak in the target shot. On a cinematic paired-view
> benchmark spanning diverse viewpoints and framings, our method lowers perceptual error by 59%,
> landmark error by 56%, and speech leakage by 97% relative to the strongest baseline, Wan 3.0.
> Our method also remains robust on in-the-wild scenes, highlighting its potential for film post-
> production.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

