---
layout: publication
title: 'Coba: Convergence Balancer For Multitask Finetuning Of Large Language Models'
authors: Zi Gong, Hang Yu, Cong Liao, Bingchang Liu, Chaoyu Chen, Jianguo Li
conference: "Arxiv"
year: 2024
bibkey: gong2024convergence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06741"}
  - {name: "Code", url: "https://github.com/codefuse-ai/MFTCoder"}
tags: ['Pretraining Methods', 'Training Techniques', 'Fine-Tuning', 'Has Code']
---
Multi-task learning (MTL) benefits the fine-tuning of large language models
(LLMs) by providing a single model with improved performance and generalization
ability across tasks, presenting a resource-efficient alternative to developing
separate models for each task. Yet, existing MTL strategies for LLMs often fall
short by either being computationally intensive or failing to ensure
simultaneous task convergence. This paper presents CoBa, a new MTL approach
designed to effectively manage task convergence balance with minimal
computational overhead. Utilizing Relative Convergence Scores (RCS), Absolute
Convergence Scores (ACS), and a Divergence Factor (DF), CoBa dynamically
adjusts task weights during the training process, ensuring that the validation
loss of all tasks progress towards convergence at an even pace while mitigating
the issue of individual task divergence. The results of our experiments
involving three disparate datasets underscore that this approach not only
fosters equilibrium in task convergence but enhances the LLMs' performance by
up to 13% relative to the second-best baselines. Code is open-sourced at
https://github.com/codefuse-ai/MFTCoder.
