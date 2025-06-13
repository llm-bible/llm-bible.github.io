---
layout: publication
title: 'Swiftkv: Fast Prefill-optimized Inference With Knowledge-preserving Model Transformation'
authors: Aurick Qiao, Zhewei Yao, Samyam Rajbhandari, Yuxiong He
conference: "Arxiv"
year: 2024
bibkey: qiao2024fast
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.03960'}
  - {name: "Code", url: 'https://github.com/snowflakedb/arctictraining'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Applications', 'Prompting', 'Reinforcement Learning']
---
LLM inference for enterprise applications, such as summarization, RAG, and code-generation, typically observe much longer prompt than generations, leading to high prefill cost and response latency. We present SwiftKV, a novel model transformation and distillation procedure targeted at reducing the prefill compute (in FLOPs) of prompt tokens while preserving high generation quality. First, SwiftKV prefills later layers' KV cache using an earlier layer's output, allowing prompt tokens to skip those later layers. Second, SwiftKV employs a lightweight knowledge-preserving distillation procedure that can adapt existing LLMs with minimal accuracy impact. Third, SwiftKV can naturally incorporate KV cache compression to improve inference performance in low-memory scenarios. Our comprehensive experiments show that SwiftKV can effectively reduce prefill computation by 25-50% across several LLM families while incurring minimum quality degradation. In the end-to-end inference serving, SwiftKV realizes up to 2x higher aggregate throughput and 60% lower time per output token. It can achieve a staggering 560 TFlops/GPU of normalized inference throughput, which translates to 16K tokens/s for Llama-3.1-70B. SwiftKV is open-sourced at https://github.com/snowflakedb/arctictraining.
