---
layout: publication
title: 'Rag-based Question Answering Over Heterogeneous Data And Text'
authors: Philipp Christmann, Gerhard Weikum
conference: "Arxiv"
year: 2024
bibkey: christmann2024rag
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.07420'}
tags: ['RAG', 'GPT', 'Applications', 'Model Architecture', 'Multimodal Models']
---
This article presents the QUASAR system for question answering over
unstructured text, structured tables, and knowledge graphs, with unified
treatment of all sources. The system adopts a RAG-based architecture, with a
pipeline of evidence retrieval followed by answer generation, with the latter
powered by a moderate-sized language model. Additionally and uniquely, QUASAR
has components for question understanding, to derive crisper input for evidence
retrieval, and for re-ranking and filtering the retrieved evidence before
feeding the most informative pieces into the answer generation. Experiments
with three different benchmarks demonstrate the high answering quality of our
approach, being on par with or better than large GPT models, while keeping the
computational cost and energy consumption orders of magnitude lower.
