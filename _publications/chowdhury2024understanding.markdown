---
layout: publication
title: 'Understanding Ranking Llms: A Mechanistic Analysis For Information Retrieval'
authors: Tanya Chowdhury, Atharva Nijasure, James Allan
conference: "Arxiv"
year: 2024
bibkey: chowdhury2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.18527"}
tags: ['Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Transformer', 'Fine-Tuning', 'Interpretability and Explainability', 'Applications']
---
Transformer networks, particularly those achieving performance comparable to
GPT models, are well known for their robust feature extraction abilities.
However, the nature of these extracted features and their alignment with
human-engineered ones remain unexplored. In this work, we investigate the
internal mechanisms of state-of-the-art, fine-tuned LLMs for passage reranking.
We employ a probing-based analysis to examine neuron activations in ranking
LLMs, identifying the presence of known human-engineered and semantic features.
Our study spans a broad range of feature categories, including lexical signals,
document structure, query-document interactions, and complex semantic
representations, to uncover underlying patterns influencing ranking decisions.
  Through experiments on four different ranking LLMs, we identify statistical
IR features that are prominently encoded in LLM activations, as well as others
that are notably missing. Furthermore, we analyze how these models respond to
out-of-distribution queries and documents, revealing distinct generalization
behaviors. By dissecting the latent representations within LLM activations, we
aim to improve both the interpretability and effectiveness of ranking models.
Our findings offer crucial insights for developing more transparent and
reliable retrieval systems, and we release all necessary scripts and code to
support further exploration.
