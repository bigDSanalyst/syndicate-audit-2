---
aliases: ["Pushing Dexterity and Safety for In-Hand Object Pose Reaching That Works Remarkably Well"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.37652"
url: "http://arxiv.org/abs/2610.37652v1"
published: "2026-10-27T17:58:20Z"
ingested: "2026-10-28T12:05:19Z"
authors:
  - "Ian Chuang"
  - "Hiya Shah"
  - "Vamsi Chilamkur"
  - "Iman Soltani"
  - "Claire Tomlin"
---

# Pushing Dexterity and Safety for In-Hand Object Pose Reaching That Works Remarkably Well

## Abstract

> Dexterous manipulation with multi-fingered hands is the next frontier of robotics, yet learned
> hand skills remain limited to simple grasps or basic repeated motions, such as rotating an
> object. As robots attempt more demanding in-hand maneuvers, safety, such as not dropping the
> object, becomes critical, yet it is rarely measured. We study in-hand object pose reaching, a
> task that demands diverse and difficult grasps: moving an object to almost any position and
> orientation within reach of the fingers, at any wrist orientation, through long sequences of
> consecutive goals. We present a recipe for training such policies for a LEAP hand in simulation
> without human data, built on a range of insights, from diverse resets and goals via generated
> grasp datasets to an adaptive friction curriculum. With careful system identification, the
> policies transfer zero-shot to the real hand, using either motion capture or a single wrist-
> mounted depth camera, and prove remarkably capable and robust. On top of the task policy, we add
> a learned residual safety filter with adjustable conservativeness, letting us tune the balance
> between performance and safety and greatly reduce object drops. In 13.3 hours of real-robot
> evaluation over 4,800 unseen goals across 4 objects and diverse wrist orientations, the state-
> based policy reaches 95.2% of goals within 2 cm and 0.4 rad, and the filter cuts its drops by
> 75% while still reaching 91.5% of goals. The policies can also spin a lightbulb held in an
> arbitrary pose, reach out-of-distribution goals, withstand fast arm motion and perturbations,
> and, needing only a wrist camera, serve as portable skills such as screwing in a lightbulb. We
> release the full recipe as a platform for studying performance, reliability, and safety in high-
> dimensional dexterous systems. Videos and more are available at https://ian-
> chuang.github.io/dexsafe/.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

