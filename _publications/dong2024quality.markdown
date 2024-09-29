---
layout: publication
title: 'QAQ: Quality Adaptive Quantization For LLM KV Cache'
authors: Dong Shichen, Cheng Wen, Qin Jiayu, Wang Wei
conference: "Arxiv"
year: 2024
bibkey: dong2024quality
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04643"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Language Modeling', 'Model Architecture', 'Quantization', 'Reinforcement Learning']
---
The emergence of LLMs has ignited a fresh surge of breakthroughs in NLP applications particularly in domains such as question-answering systems and text generation. As the need for longer context grows a significant bottleneck in model deployment emerges due to the linear expansion of the Key-Value (KV) cache with the context length. Existing methods primarily rely on various hypotheses such as sorting the KV cache based on attention scores for replacement or eviction to compress the KV cache and improve model throughput. However heuristics used by these strategies may wrongly evict essential KV cache which can significantly degrade model performance. In this paper we propose QAQ a Quality Adaptive Quantization scheme for the KV cache. We theoretically demonstrate that key cache and value cache exhibit distinct sensitivities to quantization leading to the formulation of separate quantization strategies for their non-uniform quantization. Through the integration of dedicated outlier handling as well as an improved attention-aware approach QAQ achieves up to 10x the compression ratio of the KV cache size with a neglectable impact on model performance. QAQ significantly reduces the practical hurdles of deploying LLMs opening up new possibilities for longer-context applications. The code is available at github.com/ClubieDong/KVCacheQuantization.
