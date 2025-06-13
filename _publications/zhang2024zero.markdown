---
layout: publication
title: 'ZACK: Zero-overhead LLM Inference Acceleration Via Dimensionality Compression Of The Key-value Cache'
authors: Zeyu Zhang, Haiying Shen
conference: "Arxiv"
year: 2024
bibkey: zhang2024zero
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.04107'}
tags: ['Attention Mechanism', 'Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Quantization']
---
In large-language models, memory constraints in the Key-Value Cache (KVC)
pose a challenge during inference. In this work, we propose ZACK, the first KV
dimensionality compression system that achieves zero-overhead compression and
decompression and also reduces attention computation time. It complements and
can be combined with eviction-based and quantization-based methods to further
enhance KV compression. Moreover, ZACK employs adaptive compression, tailoring
KV compression rates across heads and layers based on their contributions to
inference to maximize overall compression while maintaining an accuracy loss
constraint. Additionally, ZACK enhances the self-attention kernel to balance
the uneven workloads caused by the adaptive compression approach to further
reduce attention computation latency. Comprehensive experiments demonstrate
that when combined with ZACK, state-of-the-art eviction-based and
quantization-based methods for KV compression further reduce KV size by up to
68%, Time-To-First-Token (TTFT) by up to 44%, and Time-Between-Tokens (TBT) by
up to 55% and achieve up to 1.72X throughput under the same latency, while
maintaining 99% of the baseline accuracy. We open-sourced the code.
