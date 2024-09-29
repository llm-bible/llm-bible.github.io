---
layout: publication
title: Multimodal Graph Transformer for Multimodal Question Answering
authors: He Xuehai, Wang Xin Eric
conference: "Arxiv"
year: 2023
bibkey: he2023multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.00581"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Despite the success of Transformer models in vision and language tasks they often learn knowledge from enormous data implicitly and cannot utilize structured input data directly. On the other hand structured learning approaches such as graph neural networks (GNNs) that integrate prior information can barely compete with Transformer models. In this work we aim to benefit from both worlds and propose a novel Multimodal Graph Transformer for question answering tasks that requires performing reasoning across multiple modalities. We introduce a graph-involved plug-and-play quasi-attention mechanism to incorporate multimodal graph information acquired from text and visual data to the vanilla self-attention as effective prior. In particular we construct the text graph dense region graph and semantic graph to generate adjacency matrices and then compose them with input vision and language features to perform downstream reasoning. Such a way of regularizing self-attention with graph information significantly improves the inferring ability and helps align features from different modalities. We validate the effectiveness of Multimodal Graph Transformer over its Transformer baselines on GQA VQAv2 and MultiModalQA datasets.
