---
aliases: ["VibeVideoBench:Evaluating Multimodal Agents on Code-Driven Video Generation"]
tags: [literature/arxiv, status/triage]
arxiv_id: "2610.35864"
url: "http://arxiv.org/abs/2610.35864v1"
published: "2026-10-26T17:59:32Z"
ingested: "2026-10-27T11:35:02Z"
authors:
  - "Muxi Diao"
  - "Wenbin Xu"
  - "Lele Yang"
  - "Xuyang Ma"
  - "Yuzhe Chen"
  - "Jiankang Chen"
  - "Kaiyu Jiang"
  - "Changyi Liu"
  - "Haoyu Zhang"
  - "Hongyi Fu"
  - "Jianxiong Wang"
  - "Tianke Zhang"
  - "Haonan Fan"
  - "Yingxin Li"
  - "Bingyi Li"
  - "Xu Wang"
  - "Xuanyu Zheng"
  - "Bin Wen"
  - "Tingting Gao"
  - "Han Li"
  - "Wentao Zhang"
  - "Weiran Xu"
  - "Kongming Liang"
  - "Zhanyu Ma"
---

# VibeVideoBench:Evaluating Multimodal Agents on Code-Driven Video Generation

## Abstract

> Diffusion video models produce striking clips, but they cannot reliably render an exact formula,
> a correct chart, a ruleconsistent game or narration synchronized to on-screen events. A
> different route is emerging: multimodal agents that write code to render every frame and
> synthesize every sound. We introduce VibeVideoBench, a benchmark for evaluating agents on code-
> driven video generation. Its 239 self-contained tasks in English and Chinese span 12 categories,
> from data stories and music-driven pieces to classroom lessons and paper explainers; each asks
> an agent, running in its native harness inside a sandbox, to deliver a finished MP4 with sound
> within one hour. Evaluation is hierarchical and evidence-based: program checks of the delivery
> spec, about 13k task-specific rubric checks traced to the requirements they enforce, and five
> quality dimensions anchored per task, judged by three VLM judge panels and validated with blind
> human preferences. Across nine frontier agent systems and 2,151 scored rollouts, the benchmark
> is far from solved: GPT-6 Astra and Claude Opus 5.5 lead clearly, yet even the best system fails
> a core requirement on about a quarter of tasks. Whether a video arrives at all matters as much
> as its quality, and three quarters of the lost videos are final renders started too late, run
> too slowly or never started. The judges agree with each other and with human preferences on
> system rankings, but only moderately on individual videos.

---
## Reading Notes
*Annotations below. Update the status tag as you triage; the arxiv_id frontmatter must survive edits - it is the dedup key.*

