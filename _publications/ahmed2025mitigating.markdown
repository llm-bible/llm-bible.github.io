---
layout: publication
title: 'Mateicl: Mitigating Attention Dispersion In Large-scale In-context Learning'
authors: Murtadha Ahmed, Wenbo, Liu Yunfeng
conference: "Arxiv"
year: 2025
bibkey: ahmed2025mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.01110"}
  - {name: "Code", url: "https://github.com/amurtadha/MateICL"}
tags: ['Transformer', 'RAG', 'Model Architecture', 'Attention Mechanism', 'Has Code', 'Prompting', 'In-Context Learning']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities in
In-Context Learning (ICL). However, the fixed position length constraints in
pre-trained models limit the number of demonstration examples. Recent efforts
to extend context suffer from attention dispersion as the number of
demonstrations increases. In this paper, we introduce Mitigating Attention
Dispersion in large-scale ICL (MateICL) that enables LLMs to maintain effective
self-attention as the context size grows. We first split the context into
multiple windows, each filled to the model's context capacity, which are
processed separately. Then, we introduce an additional layer to recalibrate the
attention weights, prioritizing the query tokens as the number of
demonstrations increases. Our empirical results show that MateICL can
effectively leverage larger contexts to improve ICL performance. Compared to
retrieval-based baselines, MateICL consistently achieves better performance
without requiring an externally trained retrieval model. Despite recent
advances in inference strategies (e.g., 32k token contexts), our results
demonstrate that MateICL remains beneficial in computationally
resource-constrained settings. The code is publicly available at
https://github.com/amurtadha/MateICL.
