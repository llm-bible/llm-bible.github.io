---
layout: publication
title: 'Golden-retriever: High-fidelity Agentic Retrieval Augmented Generation For Industrial Knowledge Base'
authors: Zhiyu An, Xianzhong Ding, Yen-chun Fu, Cheng-chung Chu, Yan Li, Wan Du
conference: "Arxiv"
year: 2024
bibkey: an2024golden
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.00798'}
tags: ['Agentic', 'RAG', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
This paper introduces Golden-Retriever, designed to efficiently navigate vast
industrial knowledge bases, overcoming challenges in traditional LLM
fine-tuning and RAG frameworks with domain-specific jargon and context
interpretation. Golden-Retriever incorporates a reflection-based question
augmentation step before document retrieval, which involves identifying jargon,
clarifying its meaning based on context, and augmenting the question
accordingly. Specifically, our method extracts and lists all jargon and
abbreviations in the input question, determines the context against a
pre-defined list, and queries a jargon dictionary for extended definitions and
descriptions. This comprehensive augmentation ensures the RAG framework
retrieves the most relevant documents by providing clear context and resolving
ambiguities, significantly improving retrieval accuracy. Evaluations using
three open-source LLMs on a domain-specific question-answer dataset demonstrate
Golden-Retriever's superior performance, providing a robust solution for
efficiently integrating and querying industrial knowledge bases.
