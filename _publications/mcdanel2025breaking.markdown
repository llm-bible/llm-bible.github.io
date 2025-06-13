---
layout: publication
title: 'Pipespec: Breaking Stage Dependencies In Hierarchical LLM Decoding'
authors: Bradley Mcdanel, Sai Qian Zhang, Yunhai Hu, Zining Liu
conference: "Arxiv"
year: 2025
bibkey: mcdanel2025breaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.01572"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications']
---
Speculative decoding accelerates large language model inference by using
smaller draft models to generate candidate tokens for parallel verification.
However, current approaches are limited by sequential stage dependencies that
prevent full hardware utilization. We present PipeSpec, a framework that
generalizes speculative decoding to \\(k\\) models arranged in a hierarchical
pipeline, enabling asynchronous execution with lightweight coordination for
prediction verification and rollback. Our analytical model characterizes token
generation rates across pipeline stages and proves guaranteed throughput
improvements over traditional decoding for any non-zero acceptance rate. We
further derive closed-form expressions for steady-state verification
probabilities that explain the empirical benefits of pipeline depth.
Experimental results show that PipeSpec achieves up to 2.54\\(\times\\) speedup
while outperforming state-of-the-art methods. We validate PipeSpec across text
summarization and code generation tasks using LLaMA 2 and 3 models,
demonstrating that pipeline efficiency increases with model depth, providing a
scalable approach to accelerating LLM inference on multi-device systems.
