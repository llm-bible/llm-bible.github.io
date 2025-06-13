---
layout: publication
title: 'LIRE: Listwise Reward Enhancement For Preference Alignment'
authors: Mingye Zhu, Yi Liu, Lei Zhang, Junbo Guo, Zhendong Mao
conference: "Arxiv"
year: 2024
bibkey: zhu2024listwise
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.13516'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Applications', 'Fine-Tuning', 'Reinforcement Learning']
---
Recently, tremendous strides have been made to align the generation of Large
Language Models (LLMs) with human values to mitigate toxic or unhelpful
content. Leveraging Reinforcement Learning from Human Feedback (RLHF) proves
effective and is widely adopted by researchers. However, implementing RLHF is
complex, and its sensitivity to hyperparameters renders achieving stable
performance and scalability challenging. Furthermore, prevailing approaches to
preference alignment primarily concentrate on pairwise comparisons, with
limited exploration into multi-response scenarios, thereby overlooking the
potential richness within the candidate pool. For the above reasons, we propose
a new approach: Listwise Reward Enhancement for Preference Alignment (LIRE), a
gradient-based reward optimization approach that incorporates the offline
rewards of multiple responses into a streamlined listwise framework, thus
eliminating the need for online sampling during training. LIRE is
straightforward to implement, requiring minimal parameter tuning, and
seamlessly aligns with the pairwise paradigm while naturally extending to
multi-response scenarios. Moreover, we introduce a self-enhancement algorithm
aimed at iteratively refining the reward during training. Our experiments
demonstrate that LIRE consistently outperforms existing methods across several
benchmarks on dialogue and summarization tasks, with good transferability to
out-of-distribution data, assessed using proxy reward models and human
annotators.
