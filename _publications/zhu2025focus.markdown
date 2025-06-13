---
layout: publication
title: 'Focus Directions Make Your Language Models Pay More Attention To Relevant Contexts'
authors: Youxiang Zhu, Ruochen Li, Danqing Wang, Daniel Haehn, Xiaohui Liang
conference: "Arxiv"
year: 2025
bibkey: zhu2025focus
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.23306"}
tags: ['Model Architecture', 'Attention Mechanism', 'Reinforcement Learning']
---
Long-context large language models (LLMs) are prone to be distracted by
irrelevant contexts. The reason for distraction remains poorly understood. In
this paper, we first identify the contextual heads, a special group of
attention heads that control the overall attention of the LLM. Then, we
demonstrate that distraction arises when contextual heads fail to allocate
sufficient attention to relevant contexts and can be mitigated by increasing
attention to these contexts. We further identify focus directions, located at
the key and query activations of these heads, which enable them to allocate
more attention to relevant contexts without explicitly specifying which context
is relevant. We comprehensively evaluate the effect of focus direction on
various long-context tasks and find out focus directions could help to mitigate
the poor task alignment of the long-context LLMs. We believe our findings could
promote further research on long-context LLM alignment.
