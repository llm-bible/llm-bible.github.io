---
layout: publication
title: 'Knowledge Graph-extended Retrieval Augmented Generation For Question Answering'
authors: Jasper Linders, Jakub M. Tomczak
conference: "Arxiv"
year: 2025
bibkey: linders2025knowledge
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.08893'}
tags: ['Interpretability and Explainability', 'RAG', 'Training Techniques', 'Applications', 'Prompting', 'Ethics and Bias', 'Interpretability', 'In-Context Learning']
---
Large Language Models (LLMs) and Knowledge Graphs (KGs) offer a promising
approach to robust and explainable Question Answering (QA). While LLMs excel at
natural language understanding, they suffer from knowledge gaps and
hallucinations. KGs provide structured knowledge but lack natural language
interaction. Ideally, an AI system should be both robust to missing facts as
well as easy to communicate with. This paper proposes such a system that
integrates LLMs and KGs without requiring training, ensuring adaptability
across different KGs with minimal human effort. The resulting approach can be
classified as a specific form of a Retrieval Augmented Generation (RAG) with a
KG, thus, it is dubbed Knowledge Graph-extended Retrieval Augmented Generation
(KG-RAG). It includes a question decomposition module to enhance multi-hop
information retrieval and answer explainability. Using In-Context Learning
(ICL) and Chain-of-Thought (CoT) prompting, it generates explicit reasoning
chains processed separately to improve truthfulness. Experiments on the MetaQA
benchmark show increased accuracy for multi-hop questions, though with a slight
trade-off in single-hop performance compared to LLM with KG baselines. These
findings demonstrate KG-RAG's potential to improve transparency in QA by
bridging unstructured language understanding with structured knowledge
retrieval.
