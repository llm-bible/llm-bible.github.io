---
layout: publication
title: 'Chain Of Images For Intuitively Reasoning'
authors: Fanxu Meng, Haotong Yang, Yiding Wang, Muhan Zhang
conference: "Arxiv"
year: 2023
bibkey: meng2023chain
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.09241'}
  - {name: "Code", url: 'https://github.com/GraphPKU/CoI'}
tags: ['Has Code', 'RAG', 'Model Architecture', 'Tools', 'GPT', 'Multimodal Models', 'Reinforcement Learning']
---
The human brain is naturally equipped to comprehend and interpret visual
information rapidly. When confronted with complex problems or concepts, we use
flowcharts, sketches, and diagrams to aid our thought process. Leveraging this
inherent ability can significantly enhance logical reasoning. However, current
Large Language Models (LLMs) do not utilize such visual intuition to help their
thinking. Even the most advanced version language models (e.g., GPT-4V and
LLaVA) merely align images into textual space, which means their reasoning
processes remain purely verbal. To mitigate such limitations, we present a
Chain of Images (CoI) approach, which can convert complex language reasoning
problems to simple pattern recognition by generating a series of images as
intermediate representations. Furthermore, we have developed a CoI evaluation
dataset encompassing 15 distinct domains where images can intuitively aid
problem-solving. Based on this dataset, we aim to construct a benchmark to
assess the capability of future multimodal large-scale models to leverage
images for reasoning. In supporting our CoI reasoning, we introduce a symbolic
multimodal large language model (SyMLLM) that generates images strictly based
on language instructions and accepts both text and image as input. Experiments
on Geometry, Chess and Common Sense tasks sourced from the CoI evaluation
dataset show that CoI improves performance significantly over the pure-language
Chain of Thoughts (CoT) baselines. The code is available at
https://github.com/GraphPKU/CoI.
