---
layout: publication
title: 'Pandora''s Box Or Aladdin''s Lamp: A Comprehensive Analysis Revealing The Role Of RAG Noise In Large Language Models'
authors: Jinyang Wu, Shuai Zhang, Feihu Che, Mingkuan Feng, Chuyuan Zhang, Pengpeng Shao, Jianhua Tao
conference: "Arxiv"
year: 2024
bibkey: wu2024box
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.13533"}
  - {name: "Code", url: "https://github.com/jinyangwu/NoiserBench"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Has Code']
---
Retrieval-Augmented Generation (RAG) has emerged as a crucial method for addressing hallucinations in large language models (LLMs). While recent research has extended RAG models to complex noisy scenarios, these explorations often confine themselves to limited noise types and presuppose that noise is inherently detrimental to LLMs, potentially deviating from real-world retrieval environments and restricting practical applicability. In this paper, we define seven distinct noise types from a linguistic perspective and establish a Noise RAG Benchmark (NoiserBench), a comprehensive evaluation framework encompassing multiple datasets and reasoning tasks. Through empirical evaluation of eight representative LLMs with diverse architectures and scales, we reveal that these noises can be further categorized into two practical groups: noise that is beneficial to LLMs (aka beneficial noise) and noise that is harmful to LLMs (aka harmful noise). While harmful noise generally impairs performance, beneficial noise may enhance several aspects of model capabilities and overall performance. Our analysis offers insights for developing more robust, adaptable RAG solutions and mitigating hallucinations across diverse retrieval scenarios. Code is available at https://github.com/jinyangwu/NoiserBench.
