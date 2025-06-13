---
layout: publication
title: 'Self-augmented Preference Optimization: Off-policy Paradigms For Language Model Alignment'
authors: Yueqin Yin, Zhendong Wang, Yujia Xie, Weizhu Chen, Mingyuan Zhou
conference: "Arxiv"
year: 2024
bibkey: yin2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20830"}
  - {name: "Code", url: "https://github.com/yinyueqin/SAPO"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
Traditional language model alignment methods, such as Direct Preference
Optimization (DPO), are limited by their dependence on static, pre-collected
paired preference data, which hampers their adaptability and practical
applicability. To overcome this limitation, we introduce Self-Augmented
Preference Optimization (SAPO), an effective and scalable training paradigm
that does not require existing paired data. Building on the self-play concept,
which autonomously generates negative responses, we further incorporate an
off-policy learning pipeline to enhance data exploration and exploitation.
Specifically, we employ an Exponential Moving Average (EMA) model in
conjunction with a replay buffer to enable dynamic updates of response
segments, effectively integrating real-time feedback with insights from
historical data. Our comprehensive evaluations of the LLaMA3-8B and Mistral-7B
models across benchmarks, including the Open LLM Leaderboard, IFEval,
AlpacaEval 2.0, and MT-Bench, demonstrate that SAPO matches or surpasses
established offline contrastive baselines, such as DPO and Odds Ratio
Preference Optimization, and outperforms offline self-play methods like SPIN.
Our code is available at https://github.com/yinyueqin/SAPO
