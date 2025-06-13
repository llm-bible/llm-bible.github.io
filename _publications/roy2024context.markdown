---
layout: publication
title: 'Contregen: Context-driven Tree-structured Retrieval For Open-domain Long-form Text Generation'
authors: Kashob Kumar Roy, Pritom Saha Akash, Kevin Chen-chuan Chang, Lucian Popa
conference: "Arxiv"
year: 2024
bibkey: roy2024context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.15511"}
tags: ['Tools', 'Language Modeling', 'RAG', 'Fine-Tuning', 'Applications']
---
Open-domain long-form text generation requires generating coherent,
comprehensive responses that address complex queries with both breadth and
depth. This task is challenging due to the need to accurately capture diverse
facets of input queries. Existing iterative retrieval-augmented generation
(RAG) approaches often struggle to delve deeply into each facet of complex
queries and integrate knowledge from various sources effectively. This paper
introduces ConTReGen, a novel framework that employs a context-driven,
tree-structured retrieval approach to enhance the depth and relevance of
retrieved content. ConTReGen integrates a hierarchical, top-down in-depth
exploration of query facets with a systematic bottom-up synthesis, ensuring
comprehensive coverage and coherent integration of multifaceted information.
Extensive experiments on multiple datasets, including LFQA and ODSUM, alongside
a newly introduced dataset, ODSUM-WikiHow, demonstrate that ConTReGen
outperforms existing state-of-the-art RAG models.
