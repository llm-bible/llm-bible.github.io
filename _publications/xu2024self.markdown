---
layout: publication
title: 'Simrag: Self-improving Retrieval-augmented Generation For Adapting Large Language Models To Specialized Domains'
authors: Ran Xu, Hui Liu, Sreyashi Nag, Zhenwei Dai, Yaochen Xie, Xianfeng Tang, Chen Luo, Yang Li, Joyce C. Ho, Carl Yang, Qi He
conference: "NAACL 2025"
year: 2024
bibkey: xu2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.17952"}
tags: ['Fine-Tuning', 'RAG', 'Training Techniques', 'Prompting']
---
Retrieval-augmented generation (RAG) enhances the question-answering (QA)
abilities of large language models (LLMs) by integrating external knowledge.
However, adapting general-purpose RAG systems to specialized fields such as
science and medicine poses unique challenges due to distribution shifts and
limited access to domain-specific data. To tackle this, we propose SimRAG, a
self-training approach that equips the LLM with joint capabilities of question
answering and question generation for domain adaptation. Our method first
fine-tunes the LLM on instruction-following, question-answering, and
search-related data. Then, it prompts the same LLM to generate diverse
domain-relevant questions from unlabeled corpora, with an additional filtering
strategy to retain high-quality synthetic examples. By leveraging these
self-generated synthetic examples, the LLM can improve their performance on
domain-specific RAG tasks. Experiments on 11 datasets, spanning two backbone
sizes and three domains, demonstrate that SimRAG outperforms baselines by
1.2%--8.6%.
