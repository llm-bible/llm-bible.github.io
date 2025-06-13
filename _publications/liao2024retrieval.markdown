---
layout: publication
title: 'RUIE: Retrieval-based Unified Information Extraction Using Large Language Model'
authors: Xincheng Liao, Junwen Duan, Yixi Huang, Jianxin Wang
conference: "Arxiv"
year: 2024
bibkey: liao2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.11673"}
tags: ['Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG', 'Distillation', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
Unified information extraction (UIE) aims to extract diverse structured
information from unstructured text. While large language models (LLMs) have
shown promise for UIE, they require significant computational resources and
often struggle to generalize to unseen tasks. We propose RUIE (Retrieval-based
Unified Information Extraction), a framework that leverages in-context learning
for efficient task generalization. RUIE introduces a novel demonstration
selection mechanism combining LLM preferences with a keyword-enhanced reward
model, and employs a bi-encoder retriever trained through contrastive learning
and knowledge distillation. As the first trainable retrieval framework for UIE,
RUIE serves as a universal plugin for various LLMs. Experimental results on
eight held-out datasets demonstrate RUIE's effectiveness, with average F1-score
improvements of 19.22 and 3.22 compared to instruction-tuning methods and other
retrievers, respectively.
