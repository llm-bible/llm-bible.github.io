---
layout: publication
title: Timo\: Towards Better Temporal Reasoning For Language Models
authors: Su Zhaochen, Zhang Jun, Zhu Tong, Qu Xiaoye, Li Juntao, Zhang Min, Cheng Yu
conference: "Arxiv"
year: 2024
bibkey: su2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14192"}
  - {name: "Code", url: "https://github.com/zhaochen0110/Timo"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'RAG', 'Reinforcement Learning', 'Tools']
---
Reasoning about time is essential for Large Language Models (LLMs) to understand the world. Previous works focus on solving specific tasks primarily on time-sensitive question answering. While these methods have proven effective they cannot generalize to a wider spectrum of temporal reasoning tasks. Therefore we propose a crucial question Can we build a universal framework to handle a variety of temporal reasoning tasks To that end we systematically study 38 temporal reasoning tasks. Based on the observation that 19 tasks are directly related to mathematics we first leverage the available mathematical dataset to set a solid foundation for temporal reasoning. However the in-depth study indicates that focusing solely on mathematical enhancement falls short of addressing pure temporal reasoning tasks. To mitigate this limitation we propose a simple but effective self-critic temporal optimization method to enhance the models temporal reasoning capabilities without sacrificing general task abilities. Finally we develop Timo a model designed to excel in temporal reasoning at the 7B and 13B scales. Notably Timo outperforms the counterpart LLMs by 10.0 and 7.6 in average accuracy scores and achieves the new state-of-the-art (SOTA) performance of comparable size. Extensive experiments further validate our frameworks effectiveness and its generalization across diverse temporal tasks. The code is available at https://github.com/zhaochen0110/Timo."
