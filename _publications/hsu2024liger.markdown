---
layout: publication
title: 'Liger Kernel: Efficient Triton Kernels For LLM Training'
authors: Pin-lun Hsu, Yun Dai, Vignesh Kothapalli, Qingquan Song, Shao Tang, Siyu Zhu, Steven Shimizu, Shivam Sahni, Haowen Ning, Yanning Chen
conference: "Arxiv"
year: 2024
bibkey: hsu2024liger
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10989"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'RAG', 'Model Architecture']
---
Training Large Language Models (LLMs) efficiently at scale presents a
formidable challenge, driven by their ever-increasing computational demands and
the need for enhanced performance. In this work, we introduce Liger-Kernel, an
open-sourced set of Triton kernels developed specifically for LLM training.
With kernel optimization techniques like kernel operation fusing and input
chunking, our kernels achieve on average a 20% increase in training throughput
and a 60% reduction in GPU memory usage for popular LLMs compared to
HuggingFace implementations. In addition, Liger-Kernel is designed with
modularity, accessibility, and adaptability in mind, catering to both casual
and expert users. Comprehensive benchmarks and integration tests are built in
to ensure compatibility, performance, correctness, and convergence across
diverse computing environments and model architectures.
  The source code is available under a permissive license at:
github.com/linkedin/Liger-Kernel.
