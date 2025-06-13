---
layout: publication
title: 'RAG-RL: Advancing Retrieval-augmented Generation Via RL And Curriculum Learning'
authors: Jerry Huang, Siddarth Madala, Risham Sidhu, Cheng Niu, Hao Peng, Julia Hockenmaier, Tong Zhang
conference: "Arxiv"
year: 2025
bibkey: huang2025rag
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.12759"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Applications']
---
Retrieval-augmented generation (RAG) systems rely on retrieval models for identifying relevant contexts and answer generation models for utilizing those contexts. However, retrievers exhibit imperfect recall and precision, limiting downstream performance. We introduce RAG-RL, an answer generation model trained not only to produce answers but also to identify and cite relevant information from larger sets of retrieved contexts, shifting some of the burden of identifying relevant documents from the retriever to the answer generator. Our approach uses curriculum learning, where the model is first trained on easier examples that include only relevant contexts. Our experiments show that these training samples enable models to acquire citation and reasoning skills with greater sample efficiency and generalizability, demonstrating strong model performance even as the number of irrelevant passages increases. We benchmark our methods on three open-domain multi-hop question answering datasets and report significant gains in answer and citation accuracy. Our experiments provide empirical insights into how easier training samples can give models stronger signals for learning specific skills (e.g., citation generation) and how different components of post-training (e.g., training set construction, rule-based rewards, training sample ordering, etc.) impact final model performance.
