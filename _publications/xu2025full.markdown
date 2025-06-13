---
layout: publication
title: 'Full-step-dpo: Self-supervised Preference Optimization With Step-wise Rewards For Mathematical Reasoning'
authors: Huimin Xu, Xin Mao, Feng-lin Li, Xiaobao Wu, Wang Chen, Wei Zhang, Anh Tuan Luu
conference: "Arxiv"
year: 2025
bibkey: xu2025full
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14356"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT']
---
Direct Preference Optimization (DPO) often struggles with long-chain
mathematical reasoning. Existing approaches, such as Step-DPO, typically
improve this by focusing on the first erroneous step in the reasoning chain.
However, they overlook all other steps and rely heavily on humans or GPT-4 to
identify erroneous steps. To address these issues, we propose Full-Step-DPO, a
novel DPO framework tailored for mathematical reasoning. Instead of optimizing
only the first erroneous step, it leverages step-wise rewards from the entire
reasoning chain. This is achieved by training a self-supervised process reward
model, which automatically scores each step, providing rewards while avoiding
reliance on external signals. Furthermore, we introduce a novel step-wise DPO
loss, which dynamically updates gradients based on these step-wise rewards.
This endows stronger reasoning capabilities to language models. Extensive
evaluations on both in-domain and out-of-domain mathematical reasoning
benchmarks across various base language models, demonstrate that Full-Step-DPO
achieves superior performance compared to state-of-the-art baselines.
