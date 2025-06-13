---
layout: publication
title: 'Flashinfer: Efficient And Customizable Attention Engine For LLM Inference Serving'
authors: Zihao Ye, Lequn Chen, Ruihang Lai, Wuwei Lin, Yineng Zhang, Stephanie Wang, Tianqi Chen, Baris Kasikci, Vinod Grover, Arvind Krishnamurthy, Luis Ceze
conference: "Arxiv"
year: 2025
bibkey: ye2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.01005"}
tags: ['Transformer', 'Tools', 'Applications', 'RAG', 'Model Architecture', 'Attention Mechanism', 'Pretraining Methods']
---
Transformers, driven by attention mechanisms, form the foundation of large
language models (LLMs). As these models scale up, efficient GPU attention
kernels become essential for high-throughput and low-latency inference. Diverse
LLM applications demand flexible and high-performance attention solutions. We
present FlashInfer: a customizable and efficient attention engine for LLM
serving. FlashInfer tackles KV-cache storage heterogeneity using block-sparse
format and composable formats to optimize memory access and reduce redundancy.
It also offers a customizable attention template, enabling adaptation to
various settings through Just-In-Time (JIT) compilation. Additionally,
FlashInfer's load-balanced scheduling algorithm adjusts to dynamism of user
requests while maintaining compatibility with CUDAGraph which requires static
configuration. FlashInfer have been integrated into leading LLM serving
frameworks like SGLang, vLLM and MLC-Engine. Comprehensive kernel-level and
end-to-end evaluations demonstrate FlashInfer's ability to significantly boost
kernel performance across diverse inference scenarios: compared to
state-of-the-art LLM serving solutions, FlashInfer achieve 29-69%
inter-token-latency reduction compared to compiler backends for LLM serving
benchmark, 28-30% latency reduction for long-context inference, and 13-17%
speedup for LLM serving with parallel generation.
