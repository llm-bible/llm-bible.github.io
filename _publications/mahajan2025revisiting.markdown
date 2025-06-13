---
layout: publication
title: 'Revisiting Word Embeddings In The LLM Era'
authors: Yash Mahajan, Matthew Freestone, Sathyanarayanan Aakur, Santu Karmaker
conference: "Arxiv"
year: 2025
bibkey: mahajan2025revisiting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19607"}
tags: ['Model Architecture', 'BERT', 'Reinforcement Learning']
---
Large Language Models (LLMs) have recently shown remarkable advancement in
various NLP tasks. As such, a popular trend has emerged lately where NLP
researchers extract word/sentence/document embeddings from these large
decoder-only models and use them for various inference tasks with promising
results. However, it is still unclear whether the performance improvement of
LLM-induced embeddings is merely because of scale or whether underlying
embeddings they produce significantly differ from classical encoding models
like Word2Vec, GloVe, Sentence-BERT (SBERT) or Universal Sentence Encoder
(USE). This is the central question we investigate in the paper by
systematically comparing classical decontextualized and contextualized word
embeddings with the same for LLM-induced embeddings. Our results show that LLMs
cluster semantically related words more tightly and perform better on analogy
tasks in decontextualized settings. However, in contextualized settings,
classical models like SimCSE often outperform LLMs in sentence-level similarity
assessment tasks, highlighting their continued relevance for fine-grained
semantics.
