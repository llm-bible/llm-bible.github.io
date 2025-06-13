---
layout: publication
title: 'SEM: Reinforcement Learning For Search-efficient Large Language Models'
authors: Zeyang Sha, Shiwen Cui, Weiqiang Wang
conference: "Arxiv"
year: 2025
bibkey: sha2025reinforcement
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.07903'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Recent advancements in Large Language Models(LLMs) have demonstrated their capabilities not only in reasoning but also in invoking external tools, particularly search engines. However, teaching models to discern when to invoke search and when to rely on their internal knowledge remains a significant challenge. Existing reinforcement learning approaches often lead to redundant search behaviors, resulting in inefficiencies and over-cost. In this paper, we propose SEM, a novel post-training reinforcement learning framework that explicitly trains LLMs to optimize search usage. By constructing a balanced dataset combining MuSiQue and MMLU, we create scenarios where the model must learn to distinguish between questions it can answer directly and those requiring external retrieval. We design a structured reasoning template and employ Group Relative Policy Optimization(GRPO) to post-train the model's search behaviors. Our reward function encourages accurate answering without unnecessary search while promoting effective retrieval when needed. Experimental results demonstrate that our method significantly reduces redundant search operations while maintaining or improving answer accuracy across multiple challenging benchmarks. This framework advances the model's reasoning efficiency and extends its capability to judiciously leverage external knowledge.
