---
layout: publication
title: 'Better RAG Using Relevant Information Gain'
authors: Marc Pickett, Jeremy Hartman, Ayan Kumar Bhowmick, Raquib-ul Alam, Aditya Vempaty
conference: "Arxiv"
year: 2024
bibkey: pickett2024better
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.12101'}
tags: ['RAG', 'Efficiency and Optimization', 'Applications']
---
A common way to extend the memory of large language models (LLMs) is by
retrieval augmented generation (RAG), which inserts text retrieved from a
larger memory into an LLM's context window. However, the context window is
typically limited to several thousand tokens, which limits the number of
retrieved passages that can inform a model's response. For this reason, it's
important to avoid occupying context window space with redundant information by
ensuring a degree of diversity among retrieved passages. At the same time, the
information should also be relevant to the current task. Most prior methods
that encourage diversity among retrieved results, such as Maximal Marginal
Relevance (MMR), do so by incorporating an objective that explicitly trades off
diversity and relevance. We propose a novel simple optimization metric based on
relevant information gain, a probabilistic measure of the total information
relevant to a query for a set of retrieved results. By optimizing this metric,
diversity organically emerges from our system. When used as a drop-in
replacement for the retrieval component of a RAG system, this method yields
state-of-the-art performance on question answering tasks from the Retrieval
Augmented Generation Benchmark (RGB), outperforming existing metrics that
directly optimize for relevance and diversity.
