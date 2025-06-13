---
layout: publication
title: 'The Unreasonable Effectiveness Of Entropy Minimization In LLM Reasoning'
authors: Shivam Agarwal, Zimin Zhang, Lifan Yuan, Jiawei Han, Hao Peng
conference: "Arxiv"
year: 2025
bibkey: agarwal2025unreasonable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15134"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Entropy minimization (EM) trains the model to concentrate even more probability mass on its most confident outputs. We show that this simple objective alone, without any labeled data, can substantially improve large language models' (LLMs) performance on challenging math, physics, and coding tasks. We explore three approaches: (1) EM-FT minimizes token-level entropy similarly to instruction finetuning, but on unlabeled outputs drawn from the model; (2) EM-RL: reinforcement learning with negative entropy as the only reward to maximize; (3) EM-INF: inference-time logit adjustment to reduce entropy without any training data or parameter updates. On Qwen-7B, EM-RL, without any labeled data, achieves comparable or better performance than strong RL baselines such as GRPO and RLOO that are trained on 60K labeled examples. Furthermore, EM-INF enables Qwen-32B to match or exceed the performance of proprietary models like GPT-4o, Claude 3 Opus, and Gemini 1.5 Pro on the challenging SciCode benchmark, while being 3x more efficient than self-consistency and sequential refinement. Our findings reveal that many pretrained LLMs possess previously underappreciated reasoning capabilities that can be effectively elicited through entropy minimization alone, without any labeled data or even any parameter updates.
