---
layout: publication
title: 'Iterative Self-incentivization Empowers Large Language Models As Agentic Searchers'
authors: Zhengliang Shi, Lingyong Yan, Dawei Yin, Suzan Verberne, Maarten De Rijke, Zhaochun Ren
conference: "Arxiv"
year: 2025
bibkey: shi2025iterative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20128'}
tags: ['Agentic', 'Training Techniques', 'Applications', 'Tools', 'Reinforcement Learning']
---
Large language models (LLMs) have been widely integrated into information retrieval to advance traditional techniques. However, effectively enabling LLMs to seek accurate knowledge in complex tasks remains a challenge due to the complexity of multi-hop queries as well as the irrelevant retrieved content. To address these limitations, we propose EXSEARCH, an agentic search framework, where the LLM learns to retrieve useful information as the reasoning unfolds through a self-incentivized process. At each step, the LLM decides what to retrieve (thinking), triggers an external retriever (search), and extracts fine-grained evidence (recording) to support next-step reasoning. To enable LLM with this capability, EXSEARCH adopts a Generalized Expectation-Maximization algorithm. In the E-step, the LLM generates multiple search trajectories and assigns an importance weight to each; the M-step trains the LLM on them with a re-weighted loss function. This creates a self-incentivized loop, where the LLM iteratively learns from its own generated data, progressively improving itself for search. We further theoretically analyze this training process, establishing convergence guarantees. Extensive experiments on four knowledge-intensive benchmarks show that EXSEARCH substantially outperforms baselines, e.g., +7.8% improvement on exact match score. Motivated by these promising results, we introduce EXSEARCH-Zoo, an extension that extends our method to broader scenarios, to facilitate future work.
