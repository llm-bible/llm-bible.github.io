---
layout: publication
title: 'Learning To Think: Information-theoretic Reinforcement Fine-tuning For Llms'
authors: Jingyao Wang, Wenwen Qiang, Zeen Song, Changwen Zheng, Hui Xiong
conference: "Arxiv"
year: 2025
bibkey: wang2025learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.10425"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Large language models (LLMs) excel at complex tasks thanks to advances in reasoning abilities. However, existing methods overlook the trade-off between reasoning effectiveness and computational efficiency, often encouraging unnecessarily long reasoning chains and wasting tokens. To address this, we propose Learning to Think (L2T), an information-theoretic reinforcement fine-tuning framework for LLMs to make the models achieve optimal reasoning with fewer tokens. Specifically, L2T treats each query-response interaction as a hierarchical session of multiple episodes and proposes a universal dense process reward, i.e., quantifies the episode-wise information gain in parameters, requiring no extra annotations or task-specific evaluators. We propose a method to quickly estimate this reward based on PAC-Bayes bounds and the Fisher information matrix. Theoretical analyses show that it significantly reduces computational complexity with high estimation accuracy. By immediately rewarding each episode's contribution and penalizing excessive updates, L2T optimizes the model via reinforcement learning to maximize the use of each episode and achieve effective updates. Empirical results on various reasoning benchmarks and base models demonstrate the advantage of L2T across different tasks, boosting both reasoning effectiveness and efficiency.
