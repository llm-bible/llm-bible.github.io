---
layout: publication
title: 'Flexinfer: Breaking Memory Constraint Via Flexible And Efficient Offloading For On-device LLM Inference'
authors: Hongchao Du, Shangyu Wu, Arina Kharlamova, Nan Guan, Chun Jason Xue
conference: "Arxiv"
year: 2025
bibkey: du2025breaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.03777"}
tags: ['Efficiency and Optimization', 'Tools']
---
Large Language Models (LLMs) face challenges for on-device inference due to
high memory demands. Traditional methods to reduce memory usage often
compromise performance and lack adaptability. We propose FlexInfer, an
optimized offloading framework for on-device inference, addressing these issues
with techniques like asynchronous prefetching, balanced memory locking, and
flexible tensor preservation. These strategies enhance memory efficiency and
mitigate I/O bottlenecks, ensuring high performance within user-specified
resource constraints. Experiments demonstrate that FlexInfer significantly
improves throughput under limited resources, achieving up to 12.5 times better
performance than existing methods and facilitating the deployment of large
models on resource-constrained devices.
