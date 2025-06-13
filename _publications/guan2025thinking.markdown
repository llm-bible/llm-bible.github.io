---
layout: publication
title: 'Deeprag: Thinking To Retrieval Step By Step For Large Language Models'
authors: Xinyan Guan, Jiali Zeng, Fandong Meng, Chunlei Xin, Yaojie Lu, Hongyu Lin, Xianpei Han, Le Sun, Jie Zhou
conference: "Arxiv"
year: 2025
bibkey: guan2025thinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01142"}
tags: ['RAG', 'Efficiency and Optimization', 'Tools']
---
Large Language Models (LLMs) have shown remarkable potential in reasoning
while they still suffer from severe factual hallucinations due to timeliness,
accuracy, and coverage of parametric knowledge. Meanwhile, integrating
reasoning with retrieval-augmented generation (RAG) remains challenging due to
ineffective task decomposition and redundant retrieval, which can introduce
noise and degrade response quality. In this paper, we propose DeepRAG, a
framework that models retrieval-augmented reasoning as a Markov Decision
Process (MDP), enabling strategic and adaptive retrieval. By iteratively
decomposing queries, DeepRAG dynamically determines whether to retrieve
external knowledge or rely on parametric reasoning at each step. Experiments
show that DeepRAG improves retrieval efficiency while improving answer accuracy
by 21.99%, demonstrating its effectiveness in optimizing retrieval-augmented
reasoning.
