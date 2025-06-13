---
layout: publication
title: 'Towards A Generalist Code Embedding Model Based On Massive Data Synthesis'
authors: Chaofan Li, Jianlyu Chen, Yingxia Shao, Defu Lian, Zheng Liu
conference: "Arxiv"
year: 2025
bibkey: li2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12697"}
  - {name: "Code", url: "https://github.com/FlagOpen/FlagEmbedding/tree/master/research/BGE_Coder"}
tags: ['RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Has Code']
---
Code embedding models attract increasing attention due to the widespread popularity of retrieval-augmented generation (RAG) in software development. These models are expected to capture the rich semantic relationships inherent to code, which differ significantly from those found in text. However, existing models remain severely limited due to the scarcity of high-quality training data. In this work, we introduce \textbf\{CodeR\} (\underline\{Code\} \underline\{R\}etrieval), a state-of-the-art embedding model for general-purpose code retrieval. The superior performance of CodeR is built upon CodeR-Pile, a large-scale synthetic dataset constructed under the DRU (Diversity, Reliability, Usability) principle via a novel data synthesis pipeline. To optimize training effectiveness, we propose Annealing, a curriculum learning strategy that enables effective knowledge transfer across heterogeneous sources of data. We evaluate CodeR based on 16 diverse code retrieval tasks, where it significantly outperforms existing baselines and exhibits strong out-of-domain generalization performance. We have publicly released our code and the well-trained model to facilitate further research in this critical area. https://github.com/FlagOpen/FlagEmbedding/tree/master/research/BGE_Coder.
