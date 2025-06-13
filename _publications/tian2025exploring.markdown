---
layout: publication
title: 'Exploring The Potential Of Offline RL For Reasoning In Llms: A Preliminary Study'
authors: Xiaoyu Tian, Sitong Zhao, Haotian Wang, Shuaiting Chen, Yiping Peng, Yunjie Ji, Han Zhao, Xiangang Li
conference: "Arxiv"
year: 2025
bibkey: tian2025exploring
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.02142'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Despite significant advances in long-context reasoning by large language
models (LLMs), primarily through Online Reinforcement Learning (RL) methods,
these approaches incur substantial computational costs and complexity. In
contrast, simpler and more economical Offline RL methods remain underexplored.
To address this gap, we investigate the effectiveness of Offline RL methods,
specifically Direct Preference Optimization (DPO) and its length-desensitized
variant LD-DPO, in enhancing the reasoning capabilities of LLMs. Extensive
experiments across multiple reasoning benchmarks demonstrate that these simpler
Offline RL methods substantially improve model performance, achieving an
average enhancement of 3.3%, with a particularly notable increase of 10.1% on
the challenging Arena-Hard benchmark. Furthermore, we analyze DPO's sensitivity
to output length, emphasizing that increasing reasoning length should align
with semantic richness, as indiscriminate lengthening may adversely affect
model performance. We provide comprehensive descriptions of our data processing
and training methodologies, offering empirical evidence and practical insights
for developing more cost-effective Offline RL approaches.
