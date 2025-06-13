---
layout: publication
title: 'Critical Tokens Matter: Token-level Contrastive Estimation Enhances Llm''s Reasoning Capability'
authors: Zicheng Lin, Tian Liang, Jiahao Xu, Qiuzhi Lin, Xing Wang, Ruilin Luo, Chufan Shi, Siheng Li, Yujiu Yang, Zhaopeng Tu
conference: "Arxiv"
year: 2024
bibkey: lin2024critical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.19943"}
  - {name: "Code", url: "https://github.com/chenzhiling9954/Critical-Tokens-Matter"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Has Code']
---
Mathematical reasoning tasks pose significant challenges for large language
models (LLMs) because they require precise logical deduction and sequence
analysis. In this work, we introduce the concept of critical tokens -- elements
within reasoning trajectories that significantly influence incorrect outcomes.
We present a novel framework for identifying these tokens through rollout
sampling and demonstrate their substantial divergence from traditional error
tokens. Through extensive experiments on datasets such as GSM8K and MATH500, we
show that identifying and replacing critical tokens significantly improves
model accuracy. We propose an efficient methodology for pinpointing these
tokens in large-scale datasets using contrastive estimation and extend this
framework to enhance model training processes with direct preference
optimization (DPO). Experimental results on GSM8K and MATH500 benchmarks with
the widely used models Llama-3 (8B and 70B) and Deepseek-math (7B) demonstrate
the effectiveness of the proposed approach, cDPO. Our results underscore the
potential of leveraging critical tokens to reduce errors in reasoning tasks,
advancing the development of AI systems capable of robust logical deduction.
Our code, annotated datasets, and trained models are available at
https://github.com/chenzhiling9954/Critical-Tokens-Matter to support and
encourage future research in this promising field.
