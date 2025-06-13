---
layout: publication
title: 'Long Context Vs. RAG For Llms: An Evaluation And Revisits'
authors: Xinze Li, Yixin Cao, Yubo Ma, Aixin Sun
conference: "Arxiv"
year: 2024
bibkey: li2024long
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.01880'}
tags: ['Reinforcement Learning', 'RAG', 'Efficiency and Optimization', 'Applications']
---
Extending context windows (i.e., Long Context, LC) and using retrievers to
selectively access relevant information (i.e., Retrieval-Augmented Generation,
RAG) are the two main strategies to enable LLMs to incorporate extremely long
external contexts. This paper revisits recent studies on this topic,
highlighting their key insights and discrepancies. We then provide a more
comprehensive evaluation by filtering out questions answerable without external
context, identifying the most effective retrieval methods, and expanding the
datasets. We show that LC generally outperforms RAG in question-answering
benchmarks, especially for Wikipedia-based questions. Summarization-based
retrieval performs comparably to LC, while chunk-based retrieval lags behind.
However, RAG has advantages in dialogue-based and general question queries.
These insights underscore the trade-offs between RAG and LC strategies,
offering guidance for future optimization of LLMs with external knowledge
sources. We also provide an in-depth discussion on this topic, highlighting the
overlooked importance of context relevance in existing studies.
