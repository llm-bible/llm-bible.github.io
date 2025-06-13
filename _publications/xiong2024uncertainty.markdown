---
layout: publication
title: 'Uncomp: Uncertainty-aware Long-context Compressor For Efficient Large Language Model Inference'
authors: Jing Xiong, Jianghan Shen, Fanghua Ye, Chaofan Tao, Zhongwei Wan, Jianqiao Lu, Xun Wu, Chuanyang Zheng, Zhijiang Guo, Lingpeng Kong, Ngai Wong
conference: "Arxiv"
year: 2024
bibkey: xiong2024uncertainty
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.03090'}
tags: ['Attention Mechanism', 'RAG', 'Training Techniques', 'Model Architecture', 'Merging', 'Reinforcement Learning']
---
Deploying large language models (LLMs) is challenging due to their high
memory and computational demands, especially during long-context inference.
While key-value (KV) caching accelerates inference by reusing previously
computed keys and values, it also introduces significant memory overhead.
Existing KV cache compression methods such as eviction and merging typically
compress the KV cache after it is generated and overlook the eviction of hidden
states, failing to improve the speed of the prefilling stage. Additionally,
applying a uniform compression rate across different attention heads can harm
crucial retrieval heads in needle-in-a-haystack tasks due to excessive
compression. In this paper, we propose UNComp, an uncertainty-aware compression
scheme that leverages matrix entropy to estimate model uncertainty across
layers and heads at the token sequence level. By grouping layers and heads
based on their uncertainty, UNComp adaptively compresses both the hidden states
and the KV cache. Our method achieves a 1.6x speedup in the prefilling stage
and reduces the KV cache to 4.74% of its original size, resulting in a 6.4x
increase in throughput and a 1.4x speedup in inference with only a 1.41%
performance loss. Remarkably, in needle-in-a-haystack tasks, UNComp outperforms
the full-size KV cache even when compressed to 9.38% of its original size. Our
approach offers an efficient, training-free Grouped-Query Attention paradigm
that can be seamlessly integrated into existing KV cache schemes.
