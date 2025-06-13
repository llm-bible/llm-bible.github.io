---
layout: publication
title: 'Investigating Language Preference Of Multilingual RAG Systems'
authors: Jeonghyun Park, Hwanhee Lee
conference: "Arxiv"
year: 2025
bibkey: park2025investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11175"}
  - {name: "Code", url: "https://github.com/jeonghyunpark2002/LanguagePreference.git"}
tags: ['RAG', 'Has Code', 'Tools']
---
Multilingual Retrieval-Augmented Generation (mRAG) systems enhance language models by integrating external multilingual information to produce context-aware responses. However, mRAG systems struggle with retrieving relevant information due to linguistic variations between queries and documents, generating inconsistent responses when multilingual sources conflict. In this work, we systematically investigate language preferences in both retrieval and generation of mRAG through a series of experiments. Our analysis indicates that retrievers tend to prefer high-resource and query languages, yet this preference does not consistently improve generation performance. Moreover, we observe that generators prefer the query language or Latin scripts, leading to inconsistent outputs. To overcome these issues, we propose Dual Knowledge Multilingual RAG (DKM-RAG), a simple yet effective framework that fuses translated multilingual passages with complementary model knowledge. Empirical results demonstrate that DKM-RAG mitigates language preference in generation and enhances performance across diverse linguistic settings. Code is available at https://github.com/jeonghyunpark2002/LanguagePreference.git
