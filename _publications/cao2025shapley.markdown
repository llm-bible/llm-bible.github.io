---
layout: publication
title: 'SCAR: Shapley Credit Assignment For More Efficient RLHF'
authors: Meng Cao, Shuyuan Zhang, Xiao-wen Chang, Doina Precup
conference: "Arxiv"
year: 2025
bibkey: cao2025shapley
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20417'}
tags: ['Attention Mechanism', 'Agentic', 'RAG', 'Training Techniques', 'Model Architecture', 'Applications', 'Reinforcement Learning']
---
Reinforcement Learning from Human Feedback (RLHF) is a widely used technique for aligning Large Language Models (LLMs) with human preferences, yet it often suffers from sparse reward signals, making effective credit assignment challenging. In typical setups, the reward model provides a single scalar score for an entire generated sequence, offering little insight into which token or span-level decisions were responsible for the outcome. To address this, we propose Shapley Credit Assignment Rewards (SCAR), a novel method that leverages Shapley values in cooperative game theory. SCAR distributes the total sequence-level reward among constituent tokens or text spans based on their principled marginal contributions. This creates dense reward signals, crucially, without necessitating the training of auxiliary critique models or recourse to fine-grained human annotations at intermediate generation stages. Unlike prior dense reward methods, SCAR offers a game-theoretic foundation for fair credit attribution. Theoretically, we demonstrate that SCAR preserves the original optimal policy, and empirically, across diverse tasks including sentiment control, text summarization, and instruction tuning, we show that SCAR converges significantly faster and achieves higher final reward scores compared to standard RLHF and attention-based dense reward baselines. Our findings suggest that SCAR provides a more effective and theoretically sound method for credit assignment in RLHF, leading to more efficient alignment of LLMs.
