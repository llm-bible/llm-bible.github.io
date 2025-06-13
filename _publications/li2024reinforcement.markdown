---
layout: publication
title: 'Reinforcement Learning With Token-level Feedback For Controllable Text Generation'
authors: Wendi Li, Wei Wei, Kaihe Xu, Wenfeng Xie, Dangyang Chen, Yu Cheng
conference: "Arxiv"
year: 2024
bibkey: li2024reinforcement
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11558"}
  - {name: "Code", url: "https://github.com/WindyLee0822/CTG"}
tags: ['Agentic', 'Security', 'Reinforcement Learning', 'Language Modeling', 'RAG', 'Has Code', 'Applications']
---
To meet the requirements of real-world applications, it is essential to
control generations of large language models (LLMs). Prior research has tried
to introduce reinforcement learning (RL) into controllable text generation
while most existing methods suffer from overfitting issues (finetuning-based
methods) or semantic collapse (post-processing methods). However, current RL
methods are generally guided by coarse-grained (sentence/paragraph-level)
feedback, which may lead to suboptimal performance owing to semantic twists or
progressions within sentences. To tackle that, we propose a novel reinforcement
learning algorithm named TOLE which formulates TOken-LEvel rewards for
controllable text generation, and employs a "first-quantize-then-noise"
paradigm to enhance the robustness of the RL algorithm.Furthermore, TOLE can be
flexibly extended to multiple constraints with little computational expense.
Experimental results show that our algorithm can achieve superior performance
on both single-attribute and multi-attribute control tasks. We have released
our codes at https://github.com/WindyLee0822/CTG
