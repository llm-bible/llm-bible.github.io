---
layout: publication
title: 'Scent Of Knowledge: Optimizing Search-enhanced Reasoning With Information Foraging'
authors: Hongjin Qian, Zheng Liu
conference: "Arxiv"
year: 2025
bibkey: qian2025scent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.09316"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Applications']
---
Augmenting large language models (LLMs) with external retrieval has become a standard method to address their inherent knowledge cutoff limitations. However, traditional retrieval-augmented generation methods employ static, pre-inference retrieval strategies, making them inadequate for complex tasks involving ambiguous, multi-step, or evolving information needs. Recent advances in test-time scaling techniques have demonstrated significant potential in enabling LLMs to dynamically interact with external tools, motivating the shift toward adaptive inference-time retrieval. Inspired by Information Foraging Theory (IFT), we propose InForage, a reinforcement learning framework that formalizes retrieval-augmented reasoning as a dynamic information-seeking process. Unlike existing approaches, InForage explicitly rewards intermediate retrieval quality, encouraging LLMs to iteratively gather and integrate information through adaptive search behaviors. To facilitate training, we construct a human-guided dataset capturing iterative search and reasoning trajectories for complex, real-world web tasks. Extensive evaluations across general question answering, multi-hop reasoning tasks, and a newly developed real-time web QA dataset demonstrate InForage's superior performance over baseline methods. These results highlight InForage's effectiveness in building robust, adaptive, and efficient reasoning agents.
