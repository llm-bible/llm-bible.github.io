---
layout: publication
title: 'Do RAG Systems Suffer From Positional Bias?'
authors: Florin Cuconasu, Simone Filice, Guy Horowitz, Yoelle Maarek, Fabrizio Silvestri
conference: "Arxiv"
year: 2025
bibkey: cuconasu2025do
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.15561'}
tags: ['Ethics and Bias', 'RAG', 'Prompting', 'Tools']
---
Retrieval Augmented Generation enhances LLM accuracy by adding passages retrieved from an external corpus to the LLM prompt. This paper investigates how positional bias - the tendency of LLMs to weight information differently based on its position in the prompt - affects not only the LLM's capability to capitalize on relevant passages, but also its susceptibility to distracting passages. Through extensive experiments on three benchmarks, we show how state-of-the-art retrieval pipelines, while attempting to retrieve relevant passages, systematically bring highly distracting ones to the top ranks, with over 60% of queries containing at least one highly distracting passage among the top-10 retrieved passages. As a result, the impact of the LLM positional bias, which in controlled settings is often reported as very prominent by related works, is actually marginal in real scenarios since both relevant and distracting passages are, in turn, penalized. Indeed, our findings reveal that sophisticated strategies that attempt to rearrange the passages based on LLM positional preferences do not perform better than random shuffling.
