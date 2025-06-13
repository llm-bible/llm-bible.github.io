---
layout: publication
title: 'DINO-R1: Incentivizing Reasoning Capability In Vision Foundation Models'
authors: Chenbin Pan, Wenbin He, Zhengzhong Tu, Liu Ren
conference: "Arxiv"
year: 2025
bibkey: pan2025dino
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24025"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
The recent explosive interest in the reasoning capabilities of large language models, such as DeepSeek-R1, has demonstrated remarkable success through reinforcement learning-based fine-tuning frameworks, exemplified by methods like Group Relative Policy Optimization (GRPO). However, such reasoning abilities remain underexplored and notably absent in vision foundation models, including representation models like the DINO series. In this work, we propose \textbf\{DINO-R1\}, the first such attempt to incentivize visual in-context reasoning capabilities of vision foundation models using reinforcement learning. Specifically, DINO-R1 introduces \textbf\{Group Relative Query Optimization (GRQO)\}, a novel reinforcement-style training strategy explicitly designed for query-based representation models, which computes query-level rewards based on group-normalized alignment quality. We also apply KL-regularization to stabilize the objectness distribution to reduce the training instability. This joint optimization enables dense and expressive supervision across queries while mitigating overfitting and distributional drift. Building upon Grounding-DINO, we train a series of DINO-R1 family models that integrate a visual prompt encoder and a visual-guided query selection mechanism. Extensive experiments on COCO, LVIS, and ODinW demonstrate that DINO-R1 significantly outperforms supervised fine-tuning baselines, achieving strong generalization in both open-vocabulary and closed-set visual prompting scenarios.
