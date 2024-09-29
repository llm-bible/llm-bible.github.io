---
layout: publication
title: "Glam: Fine-tuning Large Language Models For Domain Knowledge Graph Alignment Via Neighborhood Partitioning And Generative Subgraph Encoding"
authors: Dernbach Stefan, Agarwal Khushbu, Zuniga Alejandro, Henry Michael, Choudhury Sutanay
conference: "Arxiv"
year: 2024
bibkey: dernbach2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.06764"}
tags: ['Applications', 'Fine Tuning', 'Language Modeling', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
Integrating large language models (LLMs) with knowledge graphs derived from domain-specific data represents an important advancement towards more powerful and factual reasoning. As these models grow more capable it is crucial to enable them to perform multi-step inferences over real-world knowledge graphs while minimizing hallucination. While large language models excel at conversation and text generation their ability to reason over domain-specialized graphs of interconnected entities remains limited. For example can we query a LLM to identify the optimal contact in a professional network for a specific goal based on relationships and attributes in a private database The answer is no--such capabilities lie beyond current methods. However this question underscores a critical technical gap that must be addressed. Many high-value applications in areas such as science security and e-commerce rely on proprietary knowledge graphs encoding unique structures relationships and logical constraints. We introduce a fine-tuning framework for developing Graph-aligned LAnguage Models (GLaM) that transforms a knowledge graph into an alternate text representation with labeled question-answer pairs. We demonstrate that grounding the models in specific graph-based knowledge expands the models capacity for structure-based reasoning. Our methodology leverages the large-language models generative capabilities to create the dataset and proposes an efficient alternate to retrieval-augmented generation styled methods.
