---
layout: publication
title: 'ELMS: Elasticized Large Language Models On Mobile Devices'
authors: Wangsong Yin, Rongjie Yi, Daliang Xu, Gang Huang, Mengwei Xu, Xuanzhe Liu
conference: "Arxiv"
year: 2024
bibkey: yin2024elasticized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.09071"}
tags: ['Agentic', 'Model Architecture', 'RAG', 'Pretraining Methods', 'Transformer', 'Prompting', 'Applications']
---
On-device Large Language Models (LLMs) are revolutionizing mobile AI,
enabling applications such as UI automation while addressing privacy concerns.
Currently, the standard approach involves deploying a single, robust LLM as a
universal solution for various applications, often referred to as
LLM-as-a-Service (LLMaaS). However, this approach faces a significant system
challenge: existing LLMs lack the flexibility to accommodate the diverse
Service-Level Objectives (SLOs) regarding inference latency across different
applications. To address this issue, we introduce ELMS, an on-device LLM
service designed to provide elasticity in both the model and prompt dimensions
of an LLMaaS. This system includes: A one-time neuron reordering technique,
which utilizes the inherent permutation consistency within transformer models
to create high-quality, elastic sub-models with minimal runtime switching
costs. A dual-head compact language model, which efficiently refines prompts
and coordinates the elastic adaptation between the model and the prompt. We
have implemented this elastic on-device LLM service on several off-the-shelf
(COTS) smartphones and evaluate ELMS using both standalone NLP/mobile-agent
datasets and synthesized end-to-end traces. Across a range of SLOs, ELMS
surpasses four strong baselines by up to 16.83% and 11.04% in absolute accuracy
on average, with less than 1% Time-To-First-Token (TTFT) switching overhead,
comparable memory usage, and fewer than 100 offline GPU hours.
