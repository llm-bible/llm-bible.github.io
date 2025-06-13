---
layout: publication
title: 'Cheems: A Practical Guidance For Building And Evaluating Chinese Reward Models From Scratch'
authors: Xueru Wen, Jie Lou, Zichao Li, Yaojie Lu, Xing Yu, Yuqiu Ji, Guohai Xu, Hongyu Lin, Ben He, Xianpei Han, Le Sun, Debing Zhang
conference: "Arxiv"
year: 2025
bibkey: wen2025practical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.17173"}
tags: ['Training Techniques', 'Reinforcement Learning']
---
Reward models (RMs) are crucial for aligning large language models (LLMs) with human preferences. However, most RM research is centered on English and relies heavily on synthetic resources, which leads to limited and less reliable datasets and benchmarks for Chinese. To address this gap, we introduce CheemsBench, a fully human-annotated RM evaluation benchmark within Chinese contexts, and CheemsPreference, a large-scale and diverse preference dataset annotated through human-machine collaboration to support Chinese RM training. We systematically evaluate open-source discriminative and generative RMs on CheemsBench and observe significant limitations in their ability to capture human preferences in Chinese scenarios. Additionally, based on CheemsPreference, we construct an RM that achieves state-of-the-art performance on CheemsBench, demonstrating the necessity of human supervision in RM training. Our findings reveal that scaled AI-generated data struggles to fully capture human preferences, emphasizing the importance of high-quality human supervision in RM development.
