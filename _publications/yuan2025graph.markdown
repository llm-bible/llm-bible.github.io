---
layout: publication
title: 'Strucsum: Graph-structured Reasoning For Long Document Extractive Summarization With Llms'
authors: Haohan Yuan, Sukhwa Hong, Haopeng Zhang
conference: "Arxiv"
year: 2025
bibkey: yuan2025graph
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.22950'}
tags: ['Arxiv', 'Training Techniques', 'Applications', 'Tools', 'Prompting']
---
Large language models (LLMs) have shown strong performance in zero-shot summarization, but often struggle to model document structure and identify salient information in long texts. In this work, we introduce StrucSum, a training-free prompting framework that enhances LLM reasoning through sentence-level graph structures. StrucSum injects structural signals into prompts via three targeted strategies: Neighbor-Aware Prompting (NAP) for local context, Centrality-Aware Prompting (CAP) for importance estimation, and Centrality-Guided Masking (CGM) for efficient input reduction. Experiments on ArXiv, PubMed, and Multi-News demonstrate that StrucSum consistently improves both summary quality and factual consistency over unsupervised baselines and vanilla prompting. Notably, on ArXiv, it boosts FactCC and SummaC by 19.2 and 9.7 points, indicating stronger alignment between summaries and source content. These findings suggest that structure-aware prompting is a simple yet effective approach for zero-shot extractive summarization with LLMs, without any training or task-specific tuning.
