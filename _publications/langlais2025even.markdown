---
layout: publication
title: 'Even Small Reasoners Should Quote Their Sources: Introducing The Pleias-rag Model Family'
authors: Pierre-carl Langlais, Pavel Chizhov, Mattia Nee, Carlos Rosas Hinostroza, Matthieu Delsart, Irène Girard, Othman Hicheur, Anastasia Stasenko, Ivan P. Yamshchikov
conference: "Arxiv"
year: 2025
bibkey: langlais2025even
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.18225'}
tags: ['Reinforcement Learning', 'RAG', 'Applications']
---
We introduce a new generation of small reasoning models for RAG, search, and
source summarization. Pleias-RAG-350m and Pleias-RAG-1B are mid-trained on a
large synthetic dataset emulating the retrieval of a wide variety of
multilingual open sources from the Common Corpus. They provide native support
for citation and grounding with literal quotes and reintegrate multiple
features associated with RAG workflows, such as query routing, query
reformulation, and source reranking. Pleias-RAG-350m and Pleias-RAG-1B
outperform SLMs below 4 billion parameters on standardized RAG benchmarks
(HotPotQA, 2wiki) and are competitive with popular larger models, including
Qwen-2.5-7B, Llama-3.1-8B, and Gemma-3-4B. They are the only SLMs to date
maintaining consistent RAG performance across leading European languages and
ensuring systematic reference grounding for statements. Due to their size and
ease of deployment on constrained infrastructure and higher factuality by
design, the models unlock a range of new use cases for generative AI.
