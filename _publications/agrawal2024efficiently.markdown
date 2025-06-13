---
layout: publication
title: 'Medha: Efficiently Serving Multi-million Context Length LLM Inference Requests Without Approximations'
authors: Amey Agrawal, Haoran Qiu, Junda Chen, Íñigo Goiri, Chaojie Zhang, Rayyan Shahid, Ramachandran Ramjee, Alexey Tumanov, Esha Choukse
conference: "Arxiv"
year: 2024
bibkey: agrawal2024efficiently
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.17264"}
tags: ['RAG', 'Training Techniques']
---
As large language models (LLMs) handle increasingly longer contexts, serving long inference requests of millions of tokens presents unique challenges. We show that existing work for long context inference is largely based on techniques from long context training, and does not handle the high variability in input lengths during inference. This leads to inefficient resource utilization, server fragmentation, and head-of-line (HOL) blocking.
  We present Medha, an end-to-end system for efficient long-context LLM inference that addresses these challenges through fine-grained time sharing. Medha introduces three key innovations: (1) the mechanism of adaptive prefill chunking to help mitigate HOL blocking with preemption; (2) two new parallelism strategies: Sequence Pipeline Parallelism (SPP) to reduce time-to-first-token by pipelining prefill chunks, and KV-Cache Parallelism (KVP) to lower time-peroutput-token by distributing decoding across servers; and (3) a novel input-length aware least remaining slack scheduling to meet Service Level Objectives (SLOs).
  Medha enables exact inference scaling beyond 10 million tokens, maintaining high throughput and low latency across mixed-length workloads. Compared to state-of-the-art systems, Medha reduces server fragmentation, cuts median latency by up to 30x, and improves throughput by over 5x, delivering production-scale long-context inference without compromising performance on shorter requests.
