---
layout: publication
title: Cacheblend Fast Large Language Model Serving For RAG With Cached Knowledge Fusion
authors: Yao Jiayi, Li Hanchen, Liu Yuhan, Ray Siddhant, Cheng Yihua, Zhang Qizheng, Du Kuntai, Lu Shan, Jiang Junchen
conference: "Arxiv"
year: 2024
bibkey: yao2024cacheblend
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16444"}
tags: ['Attention Mechanism', 'Merging', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) often incorporate multiple text chunks in their inputs to provide the necessary contexts. To speed up the prefill of the long LLM inputs one can pre-compute the KV cache of a text and re-use the KV cache when the context is reused as the prefix of another LLM input. However the reused text chunks are not always the input prefix and when they are not their precomputed KV caches cannot be directly used since they ignore the texts cross-attention with the preceding text in the LLM input. Thus the benefits of reusing KV caches remain largely unrealized. This paper tackles just one question when an LLM input contains multiple text chunks how to quickly combine their precomputed KV caches in order to achieve the same generation quality as the expensive full prefill (i.e. without reusing KV cache) We present CacheBlend a scheme that reuses the pre-computed KV caches regardless prefix or not and selectively recomputes the KV values of a small subset of tokens to partially update each reused KV cache. In the meantimethe small extra delay for recomputing some tokens can be pipelined with the retrieval of KV caches within the same joballowing CacheBlend to store KV caches in slower devices with more storage capacity while retrieving them without increasing the inference delay. By comparing CacheBlend with the state-of-the-art KV cache reusing schemes on three open-source LLMs of various sizes and four popular benchmark datasets of different tasks we show that CacheBlend reduces time-to-first-token (TTFT) by 2.2-3.3X and increases the inference throughput by 2.8-5X compared with full KV recompute without compromising generation quality or incurring more storage cost.
