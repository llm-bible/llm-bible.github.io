---
layout: publication
title: 'NEO: Saving GPU Memory Crisis With CPU Offloading For Online LLM Inference'
authors: Xuanlin Jiang, Yang Zhou, Shiyi Cao, Ion Stoica, Minlan Yu
conference: "Arxiv"
year: 2024
bibkey: jiang2024saving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.01142'}
tags: ['Attention Mechanism', 'Agentic', 'Agent', 'Applications', 'Model Architecture']
---
Online LLM inference powers many exciting applications such as intelligent
chatbots and autonomous agents. Modern LLM inference engines widely rely on
request batching to improve inference throughput, aiming to make it
cost-efficient when running on expensive GPU accelerators. However, the limited
GPU memory has largely limited the batch size achieved in practice, leaving
significant GPU compute resources wasted.
  We present NEO, an online LLM inference system that offloads part of
attention compute and KV cache states from the GPU to the local host CPU,
effectively increasing the GPU batch size and thus inference throughput. To
this end, NEO proposes asymmetric GPU-CPU pipelining and load-aware scheduling
to balance GPU and CPU loads and fully utilize their compute and memory
resources. We evaluate NEO on a wide range of workloads (i.e., code generation,
text summarization), GPUs (i.e., T4, A10G, H100), and LLM models (i.e., 7B, 8B,
70B). NEO achieves up to 7.5\\(\times\\), 26%, and 14% higher throughput compared
to GPU-only approach on T4, A10G, and H100 GPUs, respectively, while
maintaining the same latency; with more powerful CPUs, NEO achieves up to 79.3%
throughput gain on A10G GPU.
