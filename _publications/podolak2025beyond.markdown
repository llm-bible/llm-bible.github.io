---
layout: publication
title: 'Beyond Reproducibility: Advancing Zero-shot LLM Reranking Efficiency With Setwise Insertion'
authors: Jakub Podolak, Leon Peric, Mina Janicijevic, Roxana Petcu
conference: "Arxiv"
year: 2025
bibkey: podolak2025beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.10509"}
tags: ['Prompting', 'Efficiency and Optimization', 'Model Architecture', 'RAG']
---
This study presents a comprehensive reproducibility and extension analysis of
the Setwise prompting methodology for zero-shot ranking with Large Language
Models (LLMs), as proposed by Zhuang et al. We evaluate its effectiveness and
efficiency compared to traditional Pointwise, Pairwise, and Listwise approaches
in document ranking tasks. Our reproduction confirms the findings of Zhuang et
al., highlighting the trade-offs between computational efficiency and ranking
effectiveness in Setwise methods. Building on these insights, we introduce
Setwise Insertion, a novel approach that leverages the initial document ranking
as prior knowledge, reducing unnecessary comparisons and uncertainty by
focusing on candidates more likely to improve the ranking results. Experimental
results across multiple LLM architectures (Flan-T5, Vicuna, and Llama) show
that Setwise Insertion yields a 31% reduction in query time, a 23% reduction in
model inferences, and a slight improvement in reranking effectiveness compared
to the original Setwise method. These findings highlight the practical
advantage of incorporating prior ranking knowledge into Setwise prompting for
efficient and accurate zero-shot document reranking.
