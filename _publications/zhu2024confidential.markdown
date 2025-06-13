---
layout: publication
title: 'Confidential Computing On NVIDIA Hopper Gpus: A Performance Benchmark Study'
authors: Jianwei Zhu, Hang Yin, Peng Deng, Aline Almeida, Shunfan Zhou
conference: "Arxiv"
year: 2024
bibkey: zhu2024confidential
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.03992"}
tags: ['Reinforcement Learning']
---
This report evaluates the performance impact of enabling Trusted Execution
Environments (TEE) on NVIDIA Hopper GPUs for large language model (LLM)
inference tasks. We benchmark the overhead introduced by TEE mode across
various LLMs and token lengths, with a particular focus on the bottleneck
caused by CPU-GPU data transfers via PCIe. Our results indicate that while
there is minimal computational overhead within the GPU, the overall performance
penalty is primarily attributable to data transfer. For the majority of typical
LLM queries, the overhead remains below 7%, with larger models and longer
sequences experiencing nearly zero overhead.
