---
layout: publication
title: 'Wuneng: Hybrid State With Attention'
authors: Liu Xiao, Li Zhiyuan, Lin Yueyu
conference: "Arxiv"
year: 2025
bibkey: xiao2025hybrid
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.19191"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'RAG', 'Merging', 'Transformer', 'Attention Mechanism']
---
The WuNeng architecture introduces a novel approach to enhancing the
expressivity and power of large language models by integrating recurrent neural
network (RNN)-based RWKV-7 with advanced attention mechanisms, prioritizing
heightened contextual coherence over reducing KV cache size. Building upon the
hybrid-head concept from Hymba, WuNeng augments standard multi-head attention
with additional RWKV-7 state-driven heads, rather than replacing existing
heads, to enrich the model's representational capacity. A cross-head
interaction technique fosters dynamic synergy among standard, state-driven, and
newly introduced middle heads, leveraging concatenation, additive modulation,
and gated fusion for robust information integration. Furthermore, a multi-token
state processing mechanism harnesses the continuous RWKV-7 state to capture
intricate, sequence-wide dependencies, significantly boosting expressivity.
Remarkably, these enhancements are achieved with minimal additional parameters,
ensuring efficiency while empowering the model to excel in complex reasoning
and sequence generation tasks. WuNeng sets a new standard for balancing
expressivity and computational efficiency in modern neural architectures.
