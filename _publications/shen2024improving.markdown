---
layout: publication
title: 'Improving Reinforcement Learning From Human Feedback Using Contrastive Rewards'
authors: Shen Wei, Zhang Xiaoying, Yao Yuanshun, Zheng Rui, Guo Hongyi, Liu Yang
conference: "Arxiv"
year: 2024
bibkey: shen2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.07708"}
tags: ['Agentic', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security']
---
'Reinforcement learning from human feedback (RLHF) is the mainstream paradigm used to align large language models (LLMs) with human preferences. Yet existing RLHF heavily relies on accurate and informative reward models, which are vulnerable and sensitive to noise from various sources, e.g. human labeling errors, making the pipeline fragile. In this work, we improve the effectiveness of the reward model by introducing a penalty term on the reward, named as \textit\{contrastive rewards\}. &#37;Contrastive rewards Our approach involves two steps: (1) an offline sampling step to obtain responses to prompts that serve as baseline calculation and (2) a contrastive reward calculated using the baseline responses and used in the Proximal Policy Optimization (PPO) step. We show that contrastive rewards enable the LLM to penalize reward uncertainty, improve robustness, encourage improvement over baselines, calibrate according to task difficulty, and reduce variance in PPO. We show empirically contrastive rewards can improve RLHF substantially, evaluated by both GPTs and humans, and our method consistently outperforms strong baselines.'
