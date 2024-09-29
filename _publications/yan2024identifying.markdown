---
layout: publication
title: 3d-properties: Identifying Challenges In DPO And Charting A Path Forward
authors: Yan Yuzi, Miao Yibo, Li Jialian, Zhang Yipin, Xie Jian, Deng Zhijie, Yan Dong
conference: "Arxiv"
year: 2024
bibkey: yan2024identifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07327"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Interpretability And Explainability', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Aligning large language models (LLMs) with human preference has recently gained tremendous attention with the canonical yet costly RLHF-PPO and the simple and straightforward Direct Preference Optimization (DPO) as two examples. Despite the efficiency DPO has rarely be used in the state-of-the-art production-level LLMs implying its potential pathologies. In this work we revisit DPO with a comprehensive examination of its empirical efficacy and a systematic comparison with RLHF-PPO. We identify the (textbf3D)-properties of DPOs learning outcomes the (textbfD)rastic drop in the likelihood of rejected responses the (textbfD)egradation into LLM unlearning and the (textbfD)ispersion effect on unseen responses through experiments with both a carefully designed toy model and practical LLMs on tasks including mathematical problem-solving and instruction following. These findings inherently connect to some observations made by related works and we additionally contribute a plausible theoretical explanation for them. Accordingly we propose easy regularization methods to mitigate the issues caused by (textbf3D)-properties improving the training stability and final performance of DPO. Our contributions also include an investigation into how the distribution of the paired preference data impacts the effectiveness of DPO. We hope this work could offer research directions to narrow the gap between reward-free preference learning methods and reward-based ones.
