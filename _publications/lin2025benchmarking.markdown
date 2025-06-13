---
layout: publication
title: 'Mebench: Benchmarking Large Language Models For Cross-document Multi-entity Question Answering'
authors: Teng Lin
conference: "Arxiv"
year: 2025
bibkey: lin2025benchmarking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.18993'}
tags: ['RAG', 'Model Architecture', 'Tools', 'Applications', 'GPT', 'Reinforcement Learning']
---
Multi-entity question answering (MEQA) represents significant challenges for
large language models (LLM) and retrieval-augmented generation (RAG) systems,
which frequently struggle to consolidate scattered information across diverse
documents. While existing methods excel at single-document comprehension, they
often struggle with cross-document aggregation, particularly when resolving
entity-dense questions like "What is the distribution of ACM Fellows among
various fields of study?", which require integrating entity-centric insights
from heterogeneous sources (e.g., Wikipedia pages). To address this gap, we
introduce MEBench, a novel multi-document, multi-entity benchmark designed to
systematically evaluate LLMs' capacity to retrieve, consolidate, and reason
over fragmented information. Our benchmark comprises 4,780 questions which are
systematically categorized into three primary categories, further divided into
eight distinct types, ensuring broad coverage of real-world multi-entity
reasoning scenarios. Our experiments on state-of-the-art LLMs (e.g., GPT-4,
Llama-3) and RAG pipelines reveal critical limitations: even advanced models
achieve only 59% accuracy on MEBench. Our benchmark emphasizes the importance
of completeness and factual precision of information extraction in MEQA tasks,
using Entity-Attributed F1 (EA-F1) metric for granular evaluation of
entity-level correctness and attribution validity. MEBench not only highlights
systemic weaknesses in current LLM frameworks but also provides a foundation
for advancing robust, entity-aware QA architectures.
