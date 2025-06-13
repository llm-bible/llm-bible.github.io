---
layout: publication
title: 'PISCO: Pretty Simple Compression For Retrieval-augmented Generation'
authors: Maxime Louis, Hervé Déjean, Stéphane Clinchant
conference: "Arxiv"
year: 2025
bibkey: louis2025pretty
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.16075'}
tags: ['RAG', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Pretraining Methods']
---
Retrieval-Augmented Generation (RAG) pipelines enhance Large Language Models
(LLMs) by retrieving relevant documents, but they face scalability issues due
to high inference costs and limited context size. Document compression is a
practical solution, but current soft compression methods suffer from accuracy
losses and require extensive pretraining. In this paper, we introduce PISCO, a
novel method that achieves a 16x compression rate with minimal accuracy loss
(0-3%) across diverse RAG-based question-answering (QA) tasks. Unlike existing
approaches, PISCO requires no pretraining or annotated data, relying solely on
sequence-level knowledge distillation from document-based questions. With the
ability to fine-tune a 7-10B LLM in 48 hours on a single A100 GPU, PISCO offers
a highly efficient and scalable solution. We present comprehensive experiments
showing that PISCO outperforms existing compression models by 8% in accuracy.
