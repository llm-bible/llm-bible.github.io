---
layout: publication
title: DISTFLASHATTN: Distributed Memory-efficient Attention For Long-context Llms Training
authors: Li Dacheng, Shao Rulin, Xie Anze, Xing Eric P., Ma Xuezhe, Stoica Ion, Gonzalez Joseph E., Zhang Hao
conference: "Arxiv"
year: 2023
bibkey: li2023distributed
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03294"}
  - {name: "Code", url: "https://github.com/RulinShao/LightSeq"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
FlashAttention (Dao 2023) effectively reduces the quadratic peak memory usage to linear in training transformer-based large language models (LLMs) on a single GPU. In this paper we introduce DISTFLASHATTN a distributed memory-efficient attention mechanism optimized for long-context LLMs training. We propose three key techniques token-level workload balancing overlapping key-value communication and a rematerialization-aware gradient checkpointing algorithm. We evaluate DISTFLASHATTN on Llama-7B and variants with sequence lengths from 32K to 512K. DISTFLASHATTN achieves 8x longer sequences 4.45 - 5.64x speedup compared to Ring Self-Attention 2 - 8x longer sequences 1.24 - 2.01x speedup compared to Megatron-LM with FlashAttention. It achieves 1.67x and 1.26 - 1.88x speedup compared to recent Ring Attention and DeepSpeed-Ulysses. Code is available at https://github.com/RulinShao/LightSeq."
