---
layout: publication
title: 'Scalable In-context Learning On Tabular Data Via Retrieval-augmented Large Language Models'
authors: Xumeng Wen, Shun Zheng, Zhen Xu, Yiming Sun, Jiang Bian
conference: "Arxiv"
year: 2025
bibkey: wen2025scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.03147"}
tags: ['Training Techniques', 'Few-Shot', 'RAG', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
Recent studies have shown that large language models (LLMs), when customized
with post-training on tabular data, can acquire general tabular in-context
learning (TabICL) capabilities. These models are able to transfer effectively
across diverse data schemas and different task domains. However, existing
LLM-based TabICL approaches are constrained to few-shot scenarios due to the
sequence length limitations of LLMs, as tabular instances represented in plain
text consume substantial tokens. To address this limitation and enable scalable
TabICL for any data size, we propose retrieval-augmented LLMs tailored to
tabular data. Our approach incorporates a customized retrieval module, combined
with retrieval-guided instruction-tuning for LLMs. This enables LLMs to
effectively leverage larger datasets, achieving significantly improved
performance across 69 widely recognized datasets and demonstrating promising
scaling behavior. Extensive comparisons with state-of-the-art tabular models
reveal that, while LLM-based TabICL still lags behind well-tuned numeric models
in overall performance, it uncovers powerful algorithms under limited contexts,
enhances ensemble diversity, and excels on specific datasets. These unique
properties underscore the potential of language as a universal and accessible
interface for scalable tabular data learning.
