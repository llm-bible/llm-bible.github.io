---
layout: publication
title: 'Accessible And Portable LLM Inference By Compiling Computational Graphs Into SQL'
authors: Wenbo Sun, Qiming Guo, Wenlu Wang, Rihan Hai
conference: "Arxiv"
year: 2025
bibkey: sun2025accessible
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.02818'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods']
---
Serving large language models (LLMs) often demands specialized hardware,
dedicated frameworks, and substantial development efforts, which restrict their
accessibility, especially for edge devices and organizations with limited
technical resources. We propose a novel compiler that translates LLM inference
graphs into SQL queries, enabling relational databases, one of the most widely
used and mature software systems globally, to serve as the runtime. By mapping
neural operators such as matrix multiplication and attention into relational
primitives like joins and aggregations, our approach leverages database
capabilities, including disk-based data management and native caching.
Supporting key transformer components, such as attention mechanisms and
key-value caching, our system generates SQL pipelines for end-to-end LLM
inference. Using the Llama3 family as a case study, we demonstrate up to 30x
speedup in token generation for memory-constrained scenarios comparable to
competitive CPU-based frameworks. Our work offers an accessible, portable, and
efficient solution, facilitating the serving of LLMs across diverse deployment
environments.
