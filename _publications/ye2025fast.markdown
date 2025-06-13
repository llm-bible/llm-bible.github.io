---
layout: publication
title: 'Jupiter: Fast And Resource-efficient Collaborative Inference Of Generative Llms On Edge Devices'
authors: Shengyuan Ye, Bei Ouyang, Liekang Zeng, Tianyi Qian, Xiaowen Chu, Jian Tang, Xu Chen
conference: "Arxiv"
year: 2025
bibkey: ye2025fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.08242"}
tags: ['Tools', 'GPT', 'Efficiency and Optimization', 'Model Architecture', 'Attention Mechanism', 'Pretraining Methods']
---
Generative large language models (LLMs) have garnered significant attention
due to their exceptional capabilities in various AI tasks. Traditionally
deployed in cloud datacenters, LLMs are now increasingly moving towards more
accessible edge platforms to protect sensitive user data and ensure privacy
preservation. The limited computational resources of individual edge devices,
however, can result in excessively prolonged inference latency and overwhelmed
memory usage. While existing research has explored collaborative edge computing
to break the resource wall of individual devices, these solutions yet suffer
from massive communication overhead and under-utilization of edge resources.
Furthermore, they focus exclusively on optimizing the prefill phase, neglecting
the crucial autoregressive decoding phase for generative LLMs. To address that,
we propose Jupiter, a fast, scalable, and resource-efficient collaborative edge
AI system for generative LLM inference. Jupiter introduces a flexible pipelined
architecture as a principle and differentiates its system design according to
the differentiated characteristics of the prefill and decoding phases. For
prefill phase, Jupiter submits a novel intra-sequence pipeline parallelism and
develops a meticulous parallelism planning strategy to maximize resource
efficiency; For decoding, Jupiter devises an effective outline-based pipeline
parallel decoding mechanism combined with speculative decoding, which further
magnifies inference acceleration. Extensive evaluation based on realistic
implementation demonstrates that Jupiter remarkably outperforms
state-of-the-art approaches under various edge environment setups, achieving up
to 26.1x end-to-end latency reduction while rendering on-par generation
quality.
