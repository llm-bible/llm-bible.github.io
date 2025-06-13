---
layout: publication
title: 'Imprag: Retrieval-augmented Generation With Implicit Queries'
authors: Wenzheng Zhang, Xi Victoria Lin, Karl Stratos, Wen-tau Yih, Mingda Chen
conference: "Arxiv"
year: 2025
bibkey: zhang2025retrieval
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.02279'}
tags: ['RAG', 'Training Techniques']
---
Retrieval-Augmented Generation (RAG) systems traditionally treat retrieval and generation as separate processes, requiring explicit textual queries to connect them. This separation can limit the ability of models to generalize across diverse tasks. In this work, we propose a query-free RAG system, named ImpRAG, which integrates retrieval and generation into a unified model. ImpRAG allows models to implicitly express their information needs, eliminating the need for human-specified queries. By dividing pretrained decoder-only language models into specialized layer groups, ImpRAG optimizes retrieval and generation tasks simultaneously. Our approach employs a two-stage inference process, using the same model parameters and forward pass for both retrieval and generation, thereby minimizing the disparity between retrievers and language models. Experiments on 8 knowledge-intensive tasks demonstrate that ImpRAG achieves 3.6-11.5 improvements in exact match scores on unseen tasks with diverse formats, highlighting its effectiveness in enabling models to articulate their own information needs and generalize across tasks. Our analysis underscores the importance of balancing retrieval and generation parameters and leveraging generation perplexities as retrieval training objectives for enhanced performance.
