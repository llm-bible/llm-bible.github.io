---
layout: publication
title: 'HD-RAG: Retrieval-augmented Generation For Hybrid Documents Containing Text And Hierarchical Tables'
authors: Chi Zhang, Qiyang Chen
conference: "Arxiv"
year: 2025
bibkey: zhang2025hd
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09554"}
tags: ['RAG', 'Tools', 'Applications']
---
With the rapid advancement of large language models (LLMs),
Retrieval-Augmented Generation (RAG) effectively combines LLMs generative
capabilities with external retrieval-based information. The Hybrid Document RAG
task aims to integrate textual and hierarchical tabular data for more
comprehensive retrieval and generation in complex scenarios. However, there is
no existing dataset specifically designed for this task that includes both text
and tabular data. Additionally, existing methods struggle to retrieve relevant
tabular data and integrate it with text. Semantic similarity-based retrieval
lacks accuracy, while table-specific methods fail to handle complex
hierarchical structures effectively. Furthermore, the QA task requires complex
reasoning and calculations, further complicating the challenge. In this paper,
we propose a new large-scale dataset, DocRAGLib, specifically designed for the
question answering (QA) task scenario under Hybrid Document RAG. To tackle
these challenges, we introduce HD-RAG, a novel framework that incorporates a
row-and-column level (RCL) table representation, employs a two-stage process
combining ensemble and LLM-based retrieval, and integrates RECAP, which is
designed for multi-step reasoning and complex calculations in Document-QA
tasks. We conduct comprehensive experiments with DocRAGLib, showing that HD-RAG
outperforms existing baselines in both retrieval accuracy and QA performance,
demonstrating its effectiveness.
