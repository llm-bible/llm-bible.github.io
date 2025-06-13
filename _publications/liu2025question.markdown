---
layout: publication
title: 'Question-aware Knowledge Graph Prompting For Enhancing Large Language Models'
authors: Haochen Liu, Song Wang, Chen Chen, Jundong Li
conference: "Arxiv"
year: 2025
bibkey: liu2025question
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.23523'}
tags: ['Attention Mechanism', 'RAG', 'Training Techniques', 'Applications', 'Model Architecture', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Large Language Models (LLMs) often struggle with tasks requiring external
knowledge, such as knowledge-intensive Multiple Choice Question Answering
(MCQA). Integrating Knowledge Graphs (KGs) can enhance reasoning; however,
existing methods typically demand costly fine-tuning or retrieve noisy KG
information. Recent approaches leverage Graph Neural Networks (GNNs) to
generate KG-based input embedding prefixes as soft prompts for LLMs but fail to
account for question relevance, resulting in noisy prompts. Moreover, in MCQA
tasks, the absence of relevant KG knowledge for certain answer options remains
a significant challenge. To address these issues, we propose Question-Aware
Knowledge Graph Prompting (QAP), which incorporates question embeddings into
GNN aggregation to dynamically assess KG relevance. QAP employs global
attention to capture inter-option relationships, enriching soft prompts with
inferred knowledge. Experimental results demonstrate that QAP outperforms
state-of-the-art methods across multiple datasets, highlighting its
effectiveness.
