---
layout: publication
title: Linear Attention via Orthogonal Memory
authors: Zhang Jun, Jiang Shuyang, Feng Jiangtao, Zheng Lin, Kong Lingpeng
conference: "Arxiv"
year: 2023
bibkey: zhang2023linear
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.11135"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Efficient attentions have greatly improved the computational efficiency of Transformers. However most existing linear attention mechanisms suffer from an problem leading to inefficiencies in causal language modeling and hindering their application in long-range language models. This problem is more pronounced under language modeling with unbounded contexts. In this paper we propose inear ttention ia rthogonal memory~() to address these limitations achieving strong performance while maintaining linear complexity. employs orthogonal decomposition to compress a context into a fixed-size orthogonal memory while effectively minimizing redundancy within the context. Given that orthogonal memory compresses global information we further dissect the context to amplify fine-grained local information. Additionally we embed the relative position encoding into to improve the extrapolation ability. Experimental results show that greatly improves the efficiency of the causal language model with the best extrapolation performance and outperforms other efficient baselines. Further we endeavor to employ for unbounded language modeling and successfully scale the context length to 128K.
