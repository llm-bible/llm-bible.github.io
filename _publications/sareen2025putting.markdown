---
layout: publication
title: 'Putting The Value Back In RL: Better Test-time Scaling By Unifying LLM Reasoners With Verifiers'
authors: Kusha Sareen, Morgane M Moss, Alessandro Sordoni, Rishabh Agarwal, Arian Hosseini
conference: "Arxiv"
year: 2025
bibkey: sareen2025putting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.04842"}
tags: ['Agentic', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
Prevalent reinforcement learning~(RL) methods for fine-tuning LLM reasoners,
such as GRPO or Leave-one-out PPO, abandon the learned value function in favor
of empirically estimated returns. This hinders test-time compute scaling that
relies on using the value-function for verification. In this work, we propose
RL\\(^V\\) that augments any ``value-free'' RL method by jointly training the LLM
as both a reasoner and a generative verifier using RL-generated data, adding
verification capabilities without significant overhead. Empirically, RL\\(^V\\)
boosts MATH accuracy by over 20% with parallel sampling and enables
\\(8-32\times\\) efficient test-time compute scaling compared to the base RL
method. RL\\(^V\\) also exhibits strong generalization capabilities for both
easy-to-hard and out-of-domain tasks. Furthermore, RL\\(^V\\) achieves
\\(1.2-1.6\times\\) higher performance when jointly scaling parallel and sequential
test-time compute with a long reasoning R1 model.
