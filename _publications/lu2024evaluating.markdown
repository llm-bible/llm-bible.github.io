---
layout: publication
title: 'Wildvision: Evaluating Vision-language Models In The Wild With Human Preferences'
authors: Yujie Lu, Dongfu Jiang, Wenhu Chen, William Yang Wang, Yejin Choi, Bill Yuchen Lin
conference: "Arxiv"
year: 2024
bibkey: lu2024evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.11069'}
tags: ['GPT', 'Tools', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Responsible AI']
---
Recent breakthroughs in vision-language models (VLMs) emphasize the necessity
of benchmarking human preferences in real-world multimodal interactions. To
address this gap, we launched WildVision-Arena (WV-Arena), an online platform
that collects human preferences to evaluate VLMs. We curated WV-Bench by
selecting 500 high-quality samples from 8,000 user submissions in WV-Arena.
WV-Bench uses GPT-4 as the judge to compare each VLM with Claude-3-Sonnet,
achieving a Spearman correlation of 0.94 with the WV-Arena Elo. This
significantly outperforms other benchmarks like MMVet, MMMU, and MMStar.
  Our comprehensive analysis of 20K real-world interactions reveals important
insights into the failure cases of top-performing VLMs. For example, we find
that although GPT-4V surpasses many other models like Reka-Flash, Opus, and
Yi-VL-Plus in simple visual recognition and reasoning tasks, it still faces
challenges with subtle contextual cues, spatial reasoning, visual imagination,
and expert domain knowledge. Additionally, current VLMs exhibit issues with
hallucinations and safety when intentionally provoked. We are releasing our
chat and feedback data to further advance research in the field of VLMs.
