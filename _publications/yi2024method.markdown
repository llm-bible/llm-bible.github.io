---
layout: publication
title: 'A Method For Building Large Language Models With Predefined KV Cache Capacity'
authors: Zhonghua Yi, Ge Niu, Lei Wang, Wei Tang, Liqiu Zhang
conference: "Arxiv"
year: 2024
bibkey: yi2024method
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.15785"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
This paper introduces a novel approach, the Bounded-Cache Transformer (BCT),
for building large language models with a predefined Key-Value (KV) cache
capacity. The BCT addresses the excessive memory consumption issue in
traditional KV caches by implementing a bounded-length KV cache, which is
particularly suitable for the attention layers in Transformer decode-only
architectures. By dynamically updating the key-value vector sequences, the BCT
achieves efficient inference within limited cache capacity, significantly
reducing memory usage while maintaining model performance and system
throughput. Experimental results demonstrate that the BCT significantly reduces
memory usage while maintaining the model's inference quality, offering a new
solution for efficient inference in large language models.
