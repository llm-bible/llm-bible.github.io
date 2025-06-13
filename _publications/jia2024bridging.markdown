---
layout: publication
title: 'Bridging Relevance And Reasoning: Rationale Distillation In Retrieval-augmented Generation'
authors: Pengyue Jia, Derong Xu, Xiaopeng Li, Zhaocheng Du, Xiangyang Li, Xiangyu Zhao, Yichao Wang, Yuhao Wang, Huifeng Guo, Ruiming Tang
conference: "Arxiv"
year: 2024
bibkey: jia2024bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.08519"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Distillation']
---
The reranker and generator are two critical components in the
Retrieval-Augmented Generation (i.e., RAG) pipeline, responsible for ranking
relevant documents and generating responses. However, due to differences in
pre-training data and objectives, there is an inevitable gap between the
documents ranked as relevant by the reranker and those required by the
generator to support answering the query. To address this gap, we propose
RADIO, a novel and practical preference alignment framework with RAtionale
DIstillatiOn. Specifically, We first propose a rationale extraction method that
leverages the reasoning capabilities of Large Language Models (LLMs) to extract
the rationales necessary for answering the query. Subsequently, a
rationale-based alignment process is designed to rerank the documents based on
the extracted rationales, and fine-tune the reranker to align the preferences.
We conduct extensive experiments on two tasks across three datasets to
demonstrate the effectiveness of our approach compared to baseline methods. Our
code is released online to ease reproduction.
