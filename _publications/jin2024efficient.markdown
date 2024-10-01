---
layout: publication
title: 'Ragcache: Efficient Knowledge Caching For Retrieval-augmented Generation'
authors: Jin Chao, Zhang Zili, Jiang Xuanlin, Liu Fangyue, Liu Xin, Liu Xuanzhe, Jin Xin
conference: "Arxiv"
year: 2024
bibkey: jin2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.12457"}
tags: ['Efficiency And Optimization', 'RAG', 'Reinforcement Learning']
---
Retrieval-Augmented Generation (RAG) has shown significant improvements in various natural language processing tasks by integrating the strengths of large language models (LLMs) and external knowledge databases. However, RAG introduces long sequence generation and leads to high computation and memory costs. We propose RAGCache, a novel multilevel dynamic caching system tailored for RAG. Our analysis benchmarks current RAG systems, pinpointing the performance bottleneck (i.e., long sequence due to knowledge injection) and optimization opportunities (i.e., caching knowledge's intermediate states). Based on these insights, we design RAGCache, which organizes the intermediate states of retrieved knowledge in a knowledge tree and caches them in the GPU and host memory hierarchy. RAGCache proposes a replacement policy that is aware of LLM inference characteristics and RAG retrieval patterns. It also dynamically overlaps the retrieval and inference steps to minimize the end-to-end latency. We implement RAGCache and evaluate it on vLLM, a state-of-the-art LLM inference system and Faiss, a state-of-the-art vector database. The experimental results show that RAGCache reduces the time to first token (TTFT) by up to 4x and improves the throughput by up to 2.1x compared to vLLM integrated with Faiss.
