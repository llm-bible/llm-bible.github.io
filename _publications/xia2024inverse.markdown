---
layout: publication
title: 'Inverse-q*: Token Level Reinforcement Learning For Aligning Large Language Models Without Preference Data'
authors: Xia Han, Gao Songyang, Ge Qiming, Xi Zhiheng, Zhang Qi, Huang Xuanjing
conference: "Arxiv"
year: 2024
bibkey: xia2024inverse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.14874"}
tags: ['Agentic', 'Efficiency And Optimization', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Reinforcement Learning from Human Feedback (RLHF) has proven effective in aligning large language models with human intentions yet it often relies on complex methodologies like Proximal Policy Optimization (PPO) that require extensive hyper-parameter tuning and present challenges in sample efficiency and stability. In this paper we introduce Inverse-Q an innovative framework that transcends traditional RL methods by optimizing token-level reinforcement learning without the need for additional reward or value models. Inverse-Q leverages direct preference optimization techniques but extends them by estimating the conditionally optimal policy directly from the models responses facilitating more granular and flexible policy shaping. Our approach reduces reliance on human annotation and external supervision making it especially suitable for low-resource settings. We present extensive experimental results demonstrating that Inverse-Q not only matches but potentially exceeds the effectiveness of PPO in terms of convergence speed and the alignment of model responses with human preferences. Our findings suggest that Inverse-Q offers a practical and robust alternative to conventional RLHF approaches paving the way for more efficient and adaptable model training approaches.
