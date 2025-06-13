---
layout: publication
title: 'HS-STAR: Hierarchical Sampling For Self-taught Reasoners Via Difficulty Estimation And Budget Reallocation'
authors: Feng Xiong, Hongling Xu, Yifei Wang, Runxi Cheng, Yong Wang, Xiangxiang Chu
conference: "Arxiv"
year: 2025
bibkey: xiong2025hs
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19866"}
tags: ['Tools', 'RAG', 'Training Techniques', 'Reinforcement Learning']
---
Self-taught reasoners (STaRs) enhance the mathematical reasoning abilities of large language models (LLMs) by leveraging self-generated responses for self-training. Recent studies have incorporated reward models to guide response selection or decoding, aiming to obtain higher-quality data. However, they typically allocate a uniform sampling budget across all problems, overlooking the varying utility of problems at different difficulty levels. In this work, we conduct an empirical study and find that problems near the boundary of the LLM's reasoning capability offer significantly greater learning utility than both easy and overly difficult ones. To identify and exploit such problems, we propose HS-STaR, a Hierarchical Sampling framework for Self-Taught Reasoners. Given a fixed sampling budget, HS-STaR first performs lightweight pre-sampling with a reward-guided difficulty estimation strategy to efficiently identify boundary-level problems. Subsequently, it dynamically reallocates the remaining budget toward these high-utility problems during a re-sampling phase, maximizing the generation of valuable training data. Extensive experiments across multiple reasoning benchmarks and backbone LLMs demonstrate that HS-STaR significantly outperforms other baselines without requiring additional sampling budget.
