---
layout: publication
title: 'Position Ids Matter: An Enhanced Position Layout For Efficient Context Compression In Large Language Models'
authors: Runsong Zhao, Xin Liu, Xinyu Liu, Pengcheng Huang, Chunyang Xiao, Tong Xiao, Jingbo Zhu
conference: "Arxiv"
year: 2024
bibkey: zhao2024position
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.14364"}
tags: ['Applications', 'Ethics and Bias', 'RAG', 'Model Architecture', 'Multimodal Models']
---
Using special tokens (e.g., gist, memory, or compressed tokens) to compress context information is a common practice for large language models (LLMs). However, existing approaches often neglect that position encodings inherently induce local inductive biases in models, causing the compression process to ignore holistic contextual dependencies. We propose Enhanced Position Layout (EPL), a simple yet effective method that improves the context compression capability of LLMs by only adjusting position IDs, the numerical identifiers that specify token positions. EPL minimizes the distance between context tokens and their corresponding special tokens and at the same time maintains the sequence order in position IDs between context tokens, special tokens, and the subsequent tokens. Integrating EPL into our best performing context compression model results in 1.9 ROUGE-1 F1 improvement on out-of-domain question answering datasets in average. When extended to multimodal scenarios, EPL brings an average accuracy gain of 2.6 to vision compression LLMs.
