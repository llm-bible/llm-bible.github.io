---
layout: publication
title: 'Highly Optimized Kernels And Fine-grained Codebooks For LLM Inference On Arm Cpus'
authors: Dibakar Gope, David Mansell, Danny Loh, Ian Bratt
conference: "Arxiv"
year: 2024
bibkey: gope2024highly
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.00032'}
  - {name: "Code", url: 'https://github.com/ggerganov/llama.cpp'}
tags: ['Has Code', 'Efficiency and Optimization', 'GPT', 'Quantization', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) have transformed the way we think about language
understanding and generation, enthralling both researchers and developers.
However, deploying LLMs for inference has been a significant challenge due to
their unprecedented size and resource requirements. While quantizing model
weights to sub-byte precision has emerged as a promising solution to ease
memory pressure, the group quantization formats commonly used for LLM
quantization have significant compute overheads and a resource-intensive
dequantization process. As a result, a higher proportion of compute
instructions do not perform multiplies, i.e., real work, rendering them
unsuitable for meeting the required latency requirements for LLMs deployed on
commodity CPUs. In this work, we propose a set of highly optimized kernels to
accelerate LLM inference and unleash the full potential of CPUs, particularly
Arm CPUs. These kernels amortize the cost of loading the operands and the cost
of weight unpacking across multiple output rows. This, along with the
introduction of an optimized interleaved group data layout for weights and
decompression path optimizations to reduce unnecessary operations and
dequantization overhead while maximizing the use of vector and matrix multiply
operations, significantly improves the efficiency of MAC operations.
Furthermore, we present a groupwise non-uniform codebook-based quantization
method for ultra-low-precision quantization of LLMs to better match non-uniform
patterns in their weight distributions, demonstrating better throughput during
token generation while ensuring better quality than the state-of-the-art.
Applying these improvements to 4-bit LLMs results in a 3-3.2x improvement in
prompt processing and a 2x improvement in autoregressive decoding on Arm CPUs,
compared to LLaMA.cpp-based solution. The optimized kernels are available at
https://github.com/ggerganov/llama.cpp.
