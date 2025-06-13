---
layout: publication
title: 'Unlock The Correlation Between Supervised Fine-tuning And Reinforcement Learning In Training Code Large Language Models'
authors: Jie Chen, Xintian Han, Yu Ma, Xun Zhou, Liang Xiang
conference: "Arxiv"
year: 2024
bibkey: chen2024unlock
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10305"}
tags: ['Agentic', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
Automatic code generation has been a longstanding research topic. With the
advancement of general-purpose large language models (LLMs), the ability to
code stands out as one important measure to the model's reasoning performance.
Usually, a two-stage training paradigm is implemented to obtain a Code LLM,
namely the pretraining and the fine-tuning. Within the fine-tuning, supervised
fine-tuning (SFT), and reinforcement learning (RL) are often used to improve
the model's zero-shot ability. A large number of work has been conducted to
improve the model's performance on code-related benchmarks with either
modifications to the algorithm or refinement of the dataset. However, we still
lack a deep insight into the correlation between SFT and RL. For instance, what
kind of dataset should be used to ensure generalization, or what if we abandon
the SFT phase in fine-tuning. In this work, we make an attempt to understand
the correlation between SFT and RL. To facilitate our research, we manually
craft 100 basis python functions, called atomic functions, and then a
synthesizing pipeline is deployed to create a large number of synthetic
functions on top of the atomic ones. In this manner, we ensure that the train
and test sets remain distinct, preventing data contamination. Through
comprehensive ablation study, we find: (1) Both atomic and synthetic functions
are indispensable for SFT's generalization, and only a handful of synthetic
functions are adequate; (2) Through RL, the SFT's generalization to target
domain can be greatly enhanced, even with the same training prompts; (3)
Training RL from scratch can alleviate the over-fitting issue introduced in the
SFT phase.
