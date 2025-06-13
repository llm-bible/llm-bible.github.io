---
layout: publication
title: 'On The Influence Of Context Size And Model Choice In Retrieval-augmented Generation Systems'
authors: Juraj Vladika, Florian Matthes
conference: "Arxiv"
year: 2025
bibkey: vladika2025influence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14759"}
tags: ['RAG', 'Applications', 'Fine-Tuning', 'Reinforcement Learning']
---
Retrieval-augmented generation (RAG) has emerged as an approach to augment
large language models (LLMs) by reducing their reliance on static knowledge and
improving answer factuality. RAG retrieves relevant context snippets and
generates an answer based on them. Despite its increasing industrial adoption,
systematic exploration of RAG components is lacking, particularly regarding the
ideal size of provided context, and the choice of base LLM and retrieval
method. To help guide development of robust RAG systems, we evaluate various
context sizes, BM25 and semantic search as retrievers, and eight base LLMs.
Moving away from the usual RAG evaluation with short answers, we explore the
more challenging long-form question answering in two domains, where a good
answer has to utilize the entire context. Our findings indicate that final QA
performance improves steadily with up to 15 snippets but stagnates or declines
beyond that. Finally, we show that different general-purpose LLMs excel in the
biomedical domain than the encyclopedic one, and that open-domain evidence
retrieval in large corpora is challenging.
