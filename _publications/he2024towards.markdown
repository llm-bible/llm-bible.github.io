---
layout: publication
title: 'Camelot: Towards Large Language Models With Training-free Consolidated Associative Memory'
authors: He Zexue, Karlinsky Leonid, Kim Donghyun, Mcauley Julian, Krotov Dmitry, Feris Rogerio
conference: "Arxiv"
year: 2024
bibkey: he2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13449"}
tags: ['Attention Mechanism', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
"Large Language Models (LLMs) struggle to handle long input sequences due to high memory and runtime costs. Memory-augmented models have emerged as a promising solution to this problem, but current methods are hindered by limited memory capacity and require costly re-training to integrate with a new LLM. In this work, we introduce an associative memory module which can be coupled to any pre-trained (frozen) attention-based LLM without re-training, enabling it to handle arbitrarily long input sequences. Unlike previous methods, our associative memory module consolidates representations of individual tokens into a non-parametric distribution model, dynamically managed by properly balancing the novelty and recency of the incoming data. By retrieving information from this consolidated associative memory, the base LLM can achieve significant (up to 29.7&#37; on Arxiv) perplexity reduction in long-context modeling compared to other baselines evaluated on standard benchmarks. This architecture, which we call CAMELoT (Consolidated Associative Memory Enhanced Long Transformer), demonstrates superior performance even with a tiny context window of 128 tokens, and also enables improved in-context learning with a much larger set of demonstrations."
