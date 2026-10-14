---
aliases: ["Contact Trajectory Prompting: In-Context Transfer of Contact-Rich Behaviors from a Single Demonstration"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.18848"
url: "http://arxiv.org/abs/2610.18848v1"
published: "2026-10-13T17:58:08Z"
ingested: "2026-10-14T11:09:13Z"
authors:
  - "Xian Nie"
  - "Yujie Zang"
  - "Yuhang Zheng"
  - "Yupeng Zheng"
  - "Songen Gu"
  - "Wendi Chen"
  - "Chuan Wen"
  - "Cewu Lu"
  - "Wenchao Ding"
  - "Junchi Yan"
  - "Shuicheng Yan"
---

# Contact Trajectory Prompting: In-Context Transfer of Contact-Rich Behaviors from a Single Demonstration

## Abstract

> In-context robot learning enables robots to acquire new behaviors from demonstrations without
> test-time parameter updates. However, visual and kinematic specifications alone may not
> distinguish contact-rich behaviors that share similar motions but require different interaction
> intensities or patterns. We propose Contact Trajectory Prompting (CTP), a framework for one-shot
> transfer of contact-rich manipulation behaviors. CTP encodes motion and contact information from
> a single demonstration into an ordered contact trajectory prompt that captures their temporal
> evolution and specifies the desired physical interaction behavior. During execution, the policy
> uses online sensory feedback to retrieve interaction-relevant information from the prompt,
> conditioning closed-loop action generation on the demonstrated contact behavior. Across real-
> world wiping, rotation, and insertion tasks on objects excluded from training, CTP achieves
> 78.7% overall success, outperforming the strongest evaluated baseline by 13.0 percentage points.
> Changing only the reference demonstration enables CTP to follow contact specifications for both
> intensity and direction, including an intermediate wiping force level and clockwise or
> counterclockwise cap rotation. These results demonstrate that contact trajectories serve as
> effective behavioral specifications, extending in-context robot learning beyond motion imitation
> to physical interaction transfer. Project website: https://ctp-robotics.github.io/project_page.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

