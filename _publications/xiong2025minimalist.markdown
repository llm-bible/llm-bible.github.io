---
layout: publication
title: 'A Minimalist Approach To LLM Reasoning: From Rejection Sampling To Reinforce'
authors: Wei Xiong, Jiarui Yao, Yuhui Xu, Bo Pang, Lei Wang, Doyen Sahoo, Junnan Li, Nan Jiang, Tong Zhang, Caiming Xiong, Hanze Dong
conference: "Arxiv"
year: 2025
bibkey: xiong2025minimalist
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.11343'}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Reinforcement learning (RL) has become a prevailing approach for fine-tuning
large language models (LLMs) on complex reasoning tasks. Among recent methods,
GRPO stands out for its empirical success in training models such as
DeepSeek-R1, yet the sources of its effectiveness remain poorly understood. In
this work, we revisit GRPO from a reinforce-like algorithm perspective and
analyze its core components. Surprisingly, we find that a simple rejection
sampling baseline, RAFT, which trains only on positively rewarded samples,
yields competitive performance than GRPO and PPO. Our ablation studies reveal
that GRPO's main advantage arises from discarding prompts with entirely
incorrect responses, rather than from its reward normalization. Motivated by
this insight, we propose Reinforce-Rej, a minimal extension of policy gradient
that filters both entirely incorrect and entirely correct samples.
Reinforce-Rej improves KL efficiency and stability, serving as a lightweight
yet effective alternative to more complex RL algorithms. We advocate RAFT as a
robust and interpretable baseline, and suggest that future advances should
focus on more principled designs for incorporating negative samples, rather
than relying on them indiscriminately. Our findings provide guidance for future
work in reward-based LLM post-training.
