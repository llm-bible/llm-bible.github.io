---
layout: publication
title: Analyzing And Reducing Catastrophic Forgetting In Parameter Efficient Tuning
authors: Ren Weijieying, Li Xinlong, Wang Lei, Zhao Tianxiang, Qin Wei
conference: "Arxiv"
year: 2024
bibkey: ren2024analyzing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.18865"}
  - {name: "Code", url: "https://github.com/which47/LLMCL&#125;"}
tags: ['Fine Tuning', 'Has Code', 'Reinforcement Learning', 'Tools']
---
Existing research has shown that large language models (LLMs) exhibit remarkable performance in language understanding and generation. However when LLMs are continuously fine45;tuned on complex and diverse domain45;specific downstream tasks the inference performance on historical tasks decreases dramatically which is known as a catastrophic forgetting problem. A trade45;off needs to be kept between learning plasticity and memory stability. Plenty of existing works have explored strategies like memory replay regularization and parameter isolation but little is known about the geometric connection of various adjacent minima in the continual LLMs fine45;tuning scenarios. In this work we investigate the geometric connections of different minima through the lens of mode connectivity which means different minima can be connected by a low45;loss valley. Through extensive experiments we uncover the mode connectivity phenomenon in the LLMs continual learning scenario and find that it can strike a balance between plasticity and stability. Building upon these findings we propose a simple yet effective method called Interpolation45;based LoRA (I45;LoRA) which constructs a dual45;memory experience replay framework based on LoRA parameter interpolations. Extensive experiments and analysis on eight domain45;specific CL benchmarks demonstrate that I45;LoRA consistently show significant improvement over the previous state45;of45;the45;art approaches with up to 1137; performance gains providing a strong baseline and insights for future research on the large language model continual learning problem. Our code is available at url123;https://github.com/which47/LLMCL&#125;.
