---
layout: publication
title: 'Graphthought: Graph Combinatorial Optimization With Thought Generation'
authors: Zixiao Huang, Lifeng Guo, Junjie Sheng, Haosheng Chen, Wenhao Li, Bo Jin, Changhong Lu, Xiangfeng Wang
conference: "Arxiv"
year: 2025
bibkey: huang2025graph
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.11607'}
tags: ['RAG', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning']
---
Large language models (LLMs) have demonstrated remarkable capabilities across
various domains, especially in text processing and generative tasks. Recent
advancements in the reasoning capabilities of state-of-the-art LLMs, such as
OpenAI-o1, have significantly broadened their applicability, particularly in
complex problem-solving and logical inference. However, most existing LLMs
struggle with notable limitations in handling graph combinatorial optimization
(GCO) problems. To bridge this gap, we formally define the Optimal Thoughts
Design (OTD) problem, including its state and action thought space. We then
introduce a novel framework, GraphThought, designed to generate high-quality
thought datasets for GCO problems. Leveraging these datasets, we fine-tune the
Llama-3-8B-Instruct model to develop Llama-GT. Notably, despite its compact
8B-parameter architecture, Llama-GT matches the performance of state-of-the-art
LLMs on the GraphArena benchmark. Experimental results show that our approach
outperforms both proprietary and open-source models, even rivaling specialized
models like o1-mini. This work sets a new state-of-the-art benchmark while
challenging the prevailing notion that model scale is the primary driver of
reasoning capability.
