---
layout: publication
title: 'Rocketkv: Accelerating Long-context LLM Inference Via Two-stage KV Cache Compression'
authors: Payman Behnam, Yaosheng Fu, Ritchie Zhao, Po-an Tsai, Zhiding Yu, Alexey Tumanov
conference: "Arxiv"
year: 2025
bibkey: behnam2025accelerating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.14051'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Training Techniques', 'Model Architecture', 'Pretraining Methods']
---
Transformer-based Large Language Models rely critically on KV cache to
efficiently handle extended contexts during the decode phase. Yet, the size of
the KV cache grows proportionally with the input length, burdening both memory
bandwidth and capacity as decoding progresses. To address this challenge, we
present RocketKV, a training-free KV cache compression strategy designed
specifically to reduce both memory bandwidth and capacity demand of KV cache
during the decode phase. RocketKV contains two consecutive stages. In the first
stage, it performs coarse-grain KV cache eviction on the input sequence tokens
with SnapKV++, a method improved upon SnapKV by introducing adaptive pooling
size and full compatibility with grouped-query attention. In the second stage,
it adopts a hybrid attention method to conduct fine-grain top-k sparse
attention, approximating the attention scores by leveraging both head and
sequence dimensional reductions. Combining these two stages, RocketKV achieves
significant KV cache fetching bandwidth and storage savings while maintaining
comparable accuracy to full KV cache attention. We show that RocketKV provides
end-to-end speedup by up to 3\\(\times\\) as well as peak memory reduction by up to
31% in the decode phase on an NVIDIA H100 GPU compared to the full KV cache
baseline, while achieving negligible accuracy loss on a variety of long-context
tasks.
