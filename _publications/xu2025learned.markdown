---
layout: publication
title: 'CSPLADE: Learned Sparse Retrieval With Causal Language Models'
authors: Zhichao Xu, Aosong Feng, Yijun Tian, Haibo Ding, Lin Lee Cheong
conference: "Arxiv"
year: 2025
bibkey: xu2025learned
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.10816"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Quantization', 'Pretraining Methods', 'BERT', 'Applications', 'Attention Mechanism']
---
In recent years, dense retrieval has been the focus of information retrieval
(IR) research. While effective, dense retrieval produces uninterpretable dense
vectors, and suffers from the drawback of large index size. Learned sparse
retrieval (LSR) has emerged as promising alternative, achieving competitive
retrieval performance while also being able to leverage the classical inverted
index data structure for efficient retrieval. However, limited works have
explored scaling LSR beyond BERT scale. In this work, we identify two
challenges in training large language models (LLM) for LSR: (1) training
instability during the early stage of contrastive training; (2) suboptimal
performance due to pre-trained LLM's unidirectional attention. To address these
challenges, we propose two corresponding techniques: (1) a lightweight
adaptation training phase to eliminate training instability; (2) two model
variants to enable bidirectional information. With these techniques, we are
able to train LSR models with 8B scale LLM, and achieve competitive retrieval
performance with reduced index size. Furthermore, we are among the first to
analyze the performance-efficiency tradeoff of LLM-based LSR model through the
lens of model quantization. Our findings provide insights into adapting LLMs
for efficient retrieval modeling.
