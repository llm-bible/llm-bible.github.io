---
layout: publication
title: Prompt-prompted Adaptive Structured Pruning for Efficient LLM Generation
authors: Dong Harry, Chen Beidi, Chi Yuejie
conference: "Arxiv"
year: 2024
bibkey: dong2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.01365"}
  - {name: "Code", url: "https://github.com/hdong920/GRIFFIN"}
tags: ['ARXIV', 'Has Code', 'LLM', 'Model Architecture', 'Prompt', 'Pruning', 'Transformer']
---
With the development of transformer-based large language models (LLMs) they have been applied to many fields due to their remarkable utility but this comes at a considerable computational cost at deployment. Fortunately some methods such as pruning or constructing a mixture of experts (MoE) aim at exploiting sparsity in transformer feedforward (FF) blocks to gain boosts in speed and reduction in memory requirements. However these techniques can be very costly and inflexible in practice as they often require training or are restricted to specific types of architectures. To address this we introduce GRIFFIN a novel training-free and calibration-free method that selects unique FF experts at the sequence level for efficient generation across a plethora of LLMs with different non-ReLU activation functions. This is possible due to a critical observation that many trained LLMs naturally produce highly structured FF activation patterns within a sequence which we call flocking. Despite our methods simplicity we show with 50 of the FF parameters GRIFFIN maintains the original models performance with little to no degradation on a variety of classification and generation tasks all while improving latency (e.g. 1.29times and 1.25times speed-ups in Gemma 7B and Llama 2 13B respectively on an NVIDIA L40). Code is available at https://github.com/hdong920/GRIFFIN.
