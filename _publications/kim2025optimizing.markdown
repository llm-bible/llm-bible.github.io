---
layout: publication
title: 'Optimizing Retrieval Strategies For Financial Question Answering Documents In Retrieval-augmented Generation Systems'
authors: Sejong Kim, Hyunseo Song, Hyunwoo Seo, Hyunjun Kim
conference: "Arxiv"
year: 2025
bibkey: kim2025optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.15191"}
  - {name: "Code", url: "https://github.com/seohyunwoo-0407/GAR"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Has Code', 'Applications']
---
Retrieval-Augmented Generation (RAG) has emerged as a promising framework to
mitigate hallucinations in Large Language Models (LLMs), yet its overall
performance is dependent on the underlying retrieval system. In the finance
domain, documents such as 10-K reports pose distinct challenges due to
domain-specific vocabulary and multi-hierarchical tabular data. In this work,
we introduce an efficient, end-to-end RAG pipeline that enhances retrieval for
financial documents through a three-phase approach: pre-retrieval, retrieval,
and post-retrieval. In the pre-retrieval phase, various query and corpus
preprocessing techniques are employed to enrich input data. During the
retrieval phase, we fine-tuned state-of-the-art (SOTA) embedding models with
domain-specific knowledge and implemented a hybrid retrieval strategy that
combines dense and sparse representations. Finally, the post-retrieval phase
leverages Direct Preference Optimization (DPO) training and document selection
methods to further refine the results. Evaluations on seven financial question
answering datasets-FinDER, FinQABench, FinanceBench, TATQA, FinQA, ConvFinQA,
and MultiHiertt-demonstrate substantial improvements in retrieval performance,
leading to more accurate and contextually appropriate generation. These
findings highlight the critical role of tailored retrieval techniques in
advancing the effectiveness of RAG systems for financial applications. A fully
replicable pipeline is available on GitHub:
https://github.com/seohyunwoo-0407/GAR.
