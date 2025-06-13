---
layout: publication
title: 'Graph Retrieval-augmented LLM For Conversational Recommendation Systems'
authors: Zhangchi Qiu, Linhao Luo, Zicheng Zhao, Shirui Pan, Alan Wee-chung Liew
conference: "Arxiv"
year: 2025
bibkey: qiu2025graph
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.06430'}
tags: ['RAG', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'RecSys', 'Prompting', 'In-Context Learning']
---
Conversational Recommender Systems (CRSs) have emerged as a transformative
paradigm for offering personalized recommendations through natural language
dialogue. However, they face challenges with knowledge sparsity, as users often
provide brief, incomplete preference statements. While recent methods have
integrated external knowledge sources to mitigate this, they still struggle
with semantic understanding and complex preference reasoning. Recent Large
Language Models (LLMs) demonstrate promising capabilities in natural language
understanding and reasoning, showing significant potential for CRSs.
Nevertheless, due to the lack of domain knowledge, existing LLM-based CRSs
either produce hallucinated recommendations or demand expensive domain-specific
training, which largely limits their applicability. In this work, we present
G-CRS (Graph Retrieval-Augmented Large Language Model for Conversational
Recommender Systems), a novel training-free framework that combines graph
retrieval-augmented generation and in-context learning to enhance LLMs'
recommendation capabilities. Specifically, G-CRS employs a two-stage
retrieve-and-recommend architecture, where a GNN-based graph reasoner first
identifies candidate items, followed by Personalized PageRank exploration to
jointly discover potential items and similar user interactions. These retrieved
contexts are then transformed into structured prompts for LLM reasoning,
enabling contextually grounded recommendations without task-specific training.
Extensive experiments on two public datasets show that G-CRS achieves superior
recommendation performance compared to existing methods without requiring
task-specific training.
