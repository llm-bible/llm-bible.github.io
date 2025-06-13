---
layout: publication
title: 'Beyond Text: Optimizing RAG With Multimodal Inputs For Industrial Applications'
authors: Monica Riedler, Stefan Langer
conference: "Arxiv"
year: 2024
bibkey: riedler2024beyond
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.21943'}
tags: ['RAG', 'GPT', 'Applications', 'Model Architecture', 'Merging', 'Multimodal Models', 'Reinforcement Learning']
---
Large Language Models (LLMs) have demonstrated impressive capabilities in
answering questions, but they lack domain-specific knowledge and are prone to
hallucinations. Retrieval Augmented Generation (RAG) is one approach to address
these challenges, while multimodal models are emerging as promising AI
assistants for processing both text and images. In this paper we describe a
series of experiments aimed at determining how to best integrate multimodal
models into RAG systems for the industrial domain. The purpose of the
experiments is to determine whether including images alongside text from
documents within the industrial domain increases RAG performance and to find
the optimal configuration for such a multimodal RAG system. Our experiments
include two approaches for image processing and retrieval, as well as two LLMs
(GPT4-Vision and LLaVA) for answer synthesis. These image processing strategies
involve the use of multimodal embeddings and the generation of textual
summaries from images. We evaluate our experiments with an LLM-as-a-Judge
approach. Our results reveal that multimodal RAG can outperform single-modality
RAG settings, although image retrieval poses a greater challenge than text
retrieval. Additionally, leveraging textual summaries from images presents a
more promising approach compared to the use of multimodal embeddings, providing
more opportunities for future advancements.
