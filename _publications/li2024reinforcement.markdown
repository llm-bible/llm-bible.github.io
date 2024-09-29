---
layout: publication
title: Reinforcement Learning With Token45;level Feedback For Controllable Text Generation
authors: Li Wendi, Wei Wei, Xu Kaihe, Xie Wenfeng, Chen Dangyang, Cheng Yu
conference: "Arxiv"
year: 2024
bibkey: li2024reinforcement
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11558"}
  - {name: "Code", url: "https://github.com/WindyLee0822/CTG"}
tags: ['Agentic', 'Applications', 'Has Code', 'Language Modeling', 'RAG', 'Reinforcement Learning', 'Security']
---
To meet the requirements of real45;world applications it is essential to control generations of large language models (LLMs). Prior research has tried to introduce reinforcement learning (RL) into controllable text generation while most existing methods suffer from overfitting issues (finetuning45;based methods) or semantic collapse (post45;processing methods). However current RL methods are generally guided by coarse45;grained (sentence/paragraph45;level) feedback which may lead to suboptimal performance owing to semantic twists or progressions within sentences. To tackle that we propose a novel reinforcement learning algorithm named TOLE which formulates TOken45;LEvel rewards for controllable text generation and employs a first45;quantize45;then45;noise paradigm to enhance the robustness of the RL algorithm.Furthermore TOLE can be flexibly extended to multiple constraints with little computational expense. Experimental results show that our algorithm can achieve superior performance on both single45;attribute and multi45;attribute control tasks. We have released our codes at https://github.com/WindyLee0822/CTG
