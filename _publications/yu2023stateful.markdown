---
layout: publication
title: 'Stateful Large Language Model Serving With Pensieve'
authors: Yu Lingfan, Li Jinyang
conference: "Arxiv"
year: 2023
bibkey: yu2023stateful
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.05516"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning']
---
Large Language Models (LLMs) are wildly popular today and it is important to serve them efficiently. Existing LLM serving systems are stateless across requests. Consequently, when LLMs are used in the common setting of multi-turn conversations, a growing log of the conversation history must be processed alongside any request by the serving system at each turn, resulting in repeated processing. In this paper, we design Pensieve, a system optimized for multi-turn conversation LLM serving. Pensieve maintains the conversation state across requests by caching previously processed history to avoid duplicate processing. Pensieve's multi-tier caching strategy can utilize both GPU and CPU memory to efficiently store and retrieve cached data. Pensieve also generalizes the recent PagedAttention kernel to support attention between multiple input tokens with a GPU cache spread over non-contiguous memory. Our evaluation shows that Pensieve can achieve 13-58&#37; more throughput compared to vLLM and TensorRT-LLM and significantly reduce latency.
