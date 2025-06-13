---
layout: publication
title: 'RAMQA: A Unified Framework For Retrieval-augmented Multi-modal Question Answering'
authors: Yang Bai, Christan Earl Grant, Daisy Zhe Wang
conference: "Arxiv"
year: 2025
bibkey: bai2025unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.13297"}
  - {name: "Code", url: "https://github.com/TonyBY/RAMQA"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'RAG', 'GPT', 'Pretraining Methods', 'Has Code', 'Applications', 'Attention Mechanism']
---
Multi-modal retrieval-augmented Question Answering (MRAQA), integrating text
and images, has gained significant attention in information retrieval (IR) and
natural language processing (NLP). Traditional ranking methods rely on small
encoder-based language models, which are incompatible with modern decoder-based
generative large language models (LLMs) that have advanced various NLP tasks.
To bridge this gap, we propose RAMQA, a unified framework combining
learning-to-rank methods with generative permutation-enhanced ranking
techniques. We first train a pointwise multi-modal ranker using LLaVA as the
backbone. Then, we apply instruction tuning to train a LLaMA model for
re-ranking the top-k documents using an innovative autoregressive multi-task
learning approach. Our generative ranking model generates re-ranked document
IDs and specific answers from document candidates in various permutations.
Experiments on two MRAQA benchmarks, WebQA and MultiModalQA, show significant
improvements over strong baselines, highlighting the effectiveness of our
approach. Code and data are available at: https://github.com/TonyBY/RAMQA
