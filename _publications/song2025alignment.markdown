---
layout: publication
title: 'Ext2gen: Alignment Through Unified Extraction And Generation For Robust Retrieval-augmented Generation'
authors: Hwanjun Song, Jeonghwan Choi, Minseok Kim
conference: "Arxiv"
year: 2025
bibkey: song2025alignment
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04789"}
tags: ['Security', 'RAG', 'Reinforcement Learning']
---
Retrieval-augmented generation (RAG) enhances LLMs by integrating external
knowledge, but generation remains fragile due to the uncertain placement of
relevant chunks and retrieval-induced information overload, leading to
hallucinations. We propose Ext2Gen, a novel extract-then-generate model that
enhances RAG robustness by first extracting query-relevant sentences before
generating answers. To optimize this model, we employ preference alignment
through pairwise feedback learning, enabling the model to generate robust
answers regardless of variations in retrieval results. Extensive experiments
demonstrate that Ext2Gen effectively identifies query-relevant sentences with
high precision and recall, leading to highly reliable answers. Furthermore,
deploying our model in a RAG environment reveals that it not only boosts the
performance of the base LLM but also synergizes with advanced retrieval
strategies like query expansion. The model is available at
https://huggingface.co/DISLab/Ext2Gen-8B-R2.
