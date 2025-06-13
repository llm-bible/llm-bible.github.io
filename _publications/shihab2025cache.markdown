---
layout: publication
title: 'Cache-efficient Posterior Sampling For Reinforcement Learning With Llm-derived Priors Across Discrete And Continuous Domains'
authors: Ibne Farabi Shihab, Sanjeda Akter, Anuj Sharma
conference: "Arxiv"
year: 2025
bibkey: shihab2025cache
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.07274'}
tags: ['Reinforcement Learning', 'Agentic', 'Training Techniques', 'Tools']
---
Integrating large language models (LLMs) as priors in reinforcement learning (RL) offers significant advantages but comes with substantial computational costs. We present a principled cache-efficient framework for posterior sampling with LLM-derived priors that dramatically reduces these costs while maintaining high performance. At the core of our approach is an adaptive caching mechanism, where cache parameters are meta-optimized using surrogate gradients derived from policy performance. This design enables efficient inference across both discrete text environments (e.g., TextWorld, ALFWorld) and continuous control domains (e.g., MuJoCo), achieving a 3.8--4.7\\(\times\\) reduction in LLM queries and 4.0--12.0\\(\times\\) lower median latencies (85--93\,ms on a consumer GPU) while retaining 96--98% of uncached performance. Our theoretical analysis provides KL divergence bounds on approximation quality, validated empirically. The framework extends to offline RL, where our CQL-Prior variant improves performance by 14--29% and reduces training time by 38--40%. Extensive evaluations across a diverse suite of eight tasks demonstrate the generalizability and practical viability of LLM-guided RL in resource-constrained settings.
