---
layout: publication
title: 'Search Wisely: Mitigating Sub-optimal Agentic Searches By Reducing Uncertainty'
authors: Peilin Wu, Mian Zhang, Xinlu Zhang, Xinya Du, Zhiyu Zoey Chen
conference: "Arxiv"
year: 2025
bibkey: wu2025search
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.17281'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Reinforcement Learning']
---
Agentic Retrieval-Augmented Generation (RAG) systems enhance Large Language Models (LLMs) by enabling dynamic, multi-step reasoning and information retrieval. However, these systems often exhibit sub-optimal search behaviors like over-search (retrieving redundant information) and under-search (failing to retrieve necessary information), which hinder efficiency and reliability. This work formally defines and quantifies these behaviors, revealing their prevalence across multiple QA datasets and agentic RAG systems (e.g., one model could have avoided searching in 27.7% of its search steps). Furthermore, we demonstrate a crucial link between these inefficiencies and the models' uncertainty regarding their own knowledge boundaries, where response accuracy correlates with model's uncertainty in its search decisions. To address this, we propose \\(\beta\\)-GRPO, a reinforcement learning-based training method that incorporates confidence threshold to reward high-certainty search decisions. Experiments on seven QA benchmarks show that \\(\beta\\)-GRPO enable a 3B model with better agentic RAG ability, outperforming other strong baselines with a 4% higher average exact match score.
