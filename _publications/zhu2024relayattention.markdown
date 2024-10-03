---
layout: publication
title: 'Relayattention For Efficient Large Language Model Serving With Long System Prompts'
authors: Zhu Lei, Wang Xinjiang, Zhang Wayne, Lau Rynson W. H.
conference: "Arxiv"
year: 2024
bibkey: zhu2024relayattention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14808"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
A practical large language model (LLM) service may involve a long system prompt, which specifies the instructions, examples, and knowledge documents of the task and is reused across requests. However, the long system prompt causes throughput/latency bottlenecks as the cost of generating the next token grows w.r.t. the sequence length. This paper aims to improve the efficiency of LLM services that involve long system prompts. Our key observation is that handling these system prompts requires heavily redundant memory accesses in existing causal attention computation algorithms. Specifically, for batched requests, the cached hidden states (\ie, key-value pairs) of system prompts are transferred from off-chip DRAM to on-chip SRAM multiple times, each corresponding to an individual request. To eliminate such a redundancy, we propose RelayAttention, an attention algorithm that allows reading these hidden states from DRAM exactly once for a batch of input tokens. RelayAttention is a free lunch: it maintains the generation quality while requiring no model retraining, as it is based on a mathematical reformulation of causal attention. We have observed significant performance improvements to a production-level system, vLLM, through integration with RelayAttention. The improvements are even more profound with longer system prompts.
