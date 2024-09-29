---
layout: publication
title: Triforce Lossless Acceleration Of Long Sequence Generation With Hierarchical Speculative Decoding
authors: Sun Hanshi, Chen Zhuoming, Yang Xinyu, Tian Yuandong, Chen Beidi
conference: "Arxiv"
year: 2024
bibkey: sun2024lossless
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.11912"}
  - {name: "Code", url: "https://github.com/Infini&#45;AI&#45;Lab/TriForce"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'RAG', 'Reinforcement Learning', 'Security']
---
With large language models (LLMs) widely deployed in long content generation recently there has emerged an increasing demand for efficient long45;sequence inference support. However key45;value (KV) cache which is stored to avoid re45;computation has emerged as a critical bottleneck by growing linearly in size with the sequence length. Due to the auto45;regressive nature of LLMs the entire KV cache will be loaded for every generated token resulting in low utilization of computational cores and high latency. While various compression methods for KV cache have been proposed to alleviate this issue they suffer from degradation in generation quality. We introduce TriForce a hierarchical speculative decoding system that is scalable for long sequence generation. This approach leverages the original model weights and dynamic sparse KV cache via retrieval as a draft model which serves as an intermediate layer in the hierarchy and is further speculated by a smaller model to reduce its drafting latency. TriForce not only facilitates impressive speedups for Llama245;7B45;128K achieving up to 2.31× on an A100 GPU but also showcases scalability in handling even longer contexts. For the offloading setting on two RTX 4090 GPUs TriForce achieves 0.108s/tokenunicode123;x2014125;only half as slow as the auto45;regressive baseline on an A100 which attains 7.78× on our optimized offloading system. Additionally TriForce performs 4.86× than DeepSpeed45;Zero45;Inference on a single RTX 4090 GPU. TriForces robustness is highlighted by its consistently outstanding performance across various temperatures. The code is available at https://github.com/Infini&#45;AI&#45;Lab/TriForce.
