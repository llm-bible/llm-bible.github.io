---
layout: publication
title: 'Chunkkv: Semantic-preserving KV Cache Compression For Efficient Long-context LLM Inference'
authors: Xiang Liu, Zhenheng Tang, Peijie Dong, Zeyu Li, Yue Liu, Bo Li, Xuming Hu, Xiaowen Chu
conference: "Arxiv"
year: 2025
bibkey: liu2025semantic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.00299'}
tags: ['Reinforcement Learning', 'RAG', 'Efficiency and Optimization']
---
Large Language Models (LLMs) require significant GPU memory when processing long texts, with the key value (KV) cache consuming up to 70% of total memory during inference. Although existing compression methods reduce memory by evaluating the importance of individual tokens, they overlook critical semantic relationships between tokens, resulting in fragmented context and degraded performance. We introduce ChunkKV, which fundamentally reimagines KV cache compression by treating semantic chunks - rather than isolated tokens - as basic compression units. This approach preserves complete linguistic structures and contextual integrity, ensuring that essential meaning is retained even under aggressive compression. Our innovation includes a novel layer-wise index reuse technique that exploits the higher cross-layer similarity of preserved indices in ChunkKV, reducing computational overhead and improving throughput by 26.5%. Comprehensive evaluations on challenging benchmarks: LongBench, Needle-In-A-HayStack, GSM8K, and JailbreakV demonstrate that ChunkKV outperforms state-of-the-art methods by up to 8.7% in precision while maintaining the same compression ratio. These results confirm that semantic-aware compression significantly enhances both efficiency and performance for long-context LLM inference, providing a simple yet effective solution to the memory bottleneck problem.
