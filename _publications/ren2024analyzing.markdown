---
layout: publication
title: 'Analyzing And Reducing Catastrophic Forgetting In Parameter Efficient Tuning'
authors: Ren Weijieying, Li Xinlong, Wang Lei, Zhao Tianxiang, Qin Wei
conference: "Arxiv"
year: 2024
bibkey: ren2024analyzing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.18865"}
  - {name: "Code", url: "https://github.com/which47/LLMCL"}
tags: ['Fine Tuning', 'Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
"Existing research has shown that large language models (LLMs) exhibit remarkable performance in language understanding and generation. However, when LLMs are continuously fine-tuned on complex and diverse domain-specific downstream tasks, the inference performance on historical tasks decreases dramatically, which is known as a catastrophic forgetting problem. A trade-off needs to be kept between learning plasticity and memory stability. Plenty of existing works have explored strategies like memory replay, regularization and parameter isolation, but little is known about the geometric connection of various adjacent minima in the continual LLMs fine-tuning scenarios. In this work, we investigate the geometric connections of different minima through the lens of mode connectivity, which means different minima can be connected by a low-loss valley. Through extensive experiments, we uncover the mode connectivity phenomenon in the LLMs continual learning scenario and find that it can strike a balance between plasticity and stability. Building upon these findings, we propose a simple yet effective method called Interpolation-based LoRA (I-LoRA), which constructs a dual-memory experience replay framework based on LoRA parameter interpolations. Extensive experiments and analysis on eight domain-specific CL benchmarks demonstrate that I-LoRA consistently show significant improvement over the previous state-of-the-art approaches with up to \(11\%\) performance gains, providing a strong baseline and insights for future research on the large language model continual learning problem. Our code is available at \url\{https://github.com/which47/LLMCL\}."
