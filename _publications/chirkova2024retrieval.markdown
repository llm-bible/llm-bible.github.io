---
layout: publication
title: 'Retrieval-augmented Generation In Multilingual Settings'
authors: Chirkova Nadezhda, Rau David, Déjean Hervé, Formal Thibault, Clinchant Stéphane, Nikoulina Vassilina
conference: "Arxiv"
year: 2024
bibkey: chirkova2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01463"}
  - {name: "Code", url: "https://github.com/naver/bergen"}
tags: ['Has Code', 'Prompting', 'RAG']
---
Retrieval-augmented generation (RAG) has recently emerged as a promising solution for incorporating up-to-date or domain-specific knowledge into large language models (LLMs) and improving LLM factuality but is predominantly studied in English-only settings. In this work we consider RAG in the multilingual setting (mRAG) i.e. with user queries and the datastore in 13 languages and investigate which components and with which adjustments are needed to build a well-performing mRAG pipeline that can be used as a strong baseline in future works. Our findings highlight that despite the availability of high-quality off-the-shelf multilingual retrievers and generators task-specific prompt engineering is needed to enable generation in user languages. Moreover current evaluation metrics need adjustments for multilingual setting to account for variations in spelling named entities. The main limitations to be addressed in future works include frequent code-switching in non-Latin alphabet languages occasional fluency errors wrong reading of the provided documents or irrelevant retrieval. We release the code for the resulting mRAG baseline pipeline at https://github.com/naver/bergen."
