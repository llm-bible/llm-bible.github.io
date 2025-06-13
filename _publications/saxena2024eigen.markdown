---
layout: publication
title: 'Eigen Attention: Attention In Low-rank Space For KV Cache Compression'
authors: Utkarsh Saxena, Gobinda Saha, Sakshi Choudhary, Kaushik Roy
conference: "Arxiv"
year: 2024
bibkey: saxena2024eigen
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.05646'}
  - {name: "Code", url: 'https://github.com/UtkarshSaxena1/EigenAttn'}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture']
---
Large language models (LLMs) represent a groundbreaking advancement in the
domain of natural language processing due to their impressive reasoning
abilities. Recently, there has been considerable interest in increasing the
context lengths for these models to enhance their applicability to complex
tasks. However, at long context lengths and large batch sizes, the key-value
(KV) cache, which stores the attention keys and values, emerges as the new
bottleneck in memory usage during inference. To address this, we propose Eigen
Attention, which performs the attention operation in a low-rank space, thereby
reducing the KV cache memory overhead. Our proposed approach is orthogonal to
existing KV cache compression techniques and can be used synergistically with
them. Through extensive experiments over OPT, MPT, and Llama model families, we
demonstrate that Eigen Attention results in up to 40% reduction in KV cache
sizes and up to 60% reduction in attention operation latency with minimal drop
in performance. Code is available at
https://github.com/UtkarshSaxena1/EigenAttn.
