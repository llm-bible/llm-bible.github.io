---
layout: publication
title: 'Retrieving Examples From Memory For Retrieval Augmented Neural Machine Translation: A Systematic Comparison'
authors: Maxime Bouthors, Josep Crego, Francois Yvon
conference: "Arxiv"
year: 2024
bibkey: bouthors2024retrieving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.02835'}
tags: ['Language Modeling', 'RAG', 'GPT', 'Applications', 'Model Architecture', 'Prompting', 'In-Context Learning', 'Pretraining Methods']
---
Retrieval-Augmented Neural Machine Translation (RAMT) architectures retrieve
examples from memory to guide the generation process. While most works in this
trend explore new ways to exploit the retrieved examples, the upstream
retrieval step is mostly unexplored. In this paper, we study the effect of
varying retrieval methods for several translation architectures, to better
understand the interplay between these two processes. We conduct experiments in
two language pairs in a multi-domain setting and consider several downstream
architectures based on a standard autoregressive model, an edit-based model,
and a large language model with in-context learning. Our experiments show that
the choice of the retrieval technique impacts the translation scores, with
variance across architectures. We also discuss the effects of increasing the
number and diversity of examples, which are mostly positive across the board.
