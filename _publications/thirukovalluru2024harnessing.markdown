---
layout: publication
title: 'Geneol: Harnessing The Generative Power Of Llms For Training-free Sentence Embeddings'
authors: Raghuveer Thirukovalluru, Bhuwan Dhingra
conference: "Arxiv"
year: 2024
bibkey: thirukovalluru2024harnessing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.14635'}
tags: ['RAG', 'Training Techniques', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Training-free embedding methods directly leverage pretrained large language
models (LLMs) to embed text, bypassing the costly and complex procedure of
contrastive learning. Previous training-free embedding methods have mainly
focused on optimizing embedding prompts and have overlooked the benefits of
utilizing the generative abilities of LLMs. We propose a novel method, GenEOL,
which uses LLMs to generate diverse transformations of a sentence that preserve
its meaning, and aggregates the resulting embeddings of these transformations
to enhance the overall sentence embedding. GenEOL significantly outperforms the
existing training-free embedding methods by an average of 2.85 points across
several LLMs on the sentence semantic text similarity (STS) benchmark. GenEOL
also achieves notable gains in clustering, reranking, and pair-classification
tasks from the MTEB benchmark. Additionally, GenEOL stabilizes representation
quality across LLM layers and remains robust to perturbations of embedding
prompts.
