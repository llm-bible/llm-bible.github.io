---
layout: publication
title: 'Mindful-rag: A Study Of Points Of Failure In Retrieval Augmented Generation'
authors: Agrawal Garima, Kumarage Tharindu, Alghamdi Zeyad, Liu Huan
conference: "Arxiv"
year: 2024
bibkey: agrawal2024mindful
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12216"}
tags: ['Applications', 'RAG', 'Tools']
---
Large Language Models (LLMs) are proficient at generating coherent and
contextually relevant text but face challenges when addressing
knowledge-intensive queries in domain-specific and factual question-answering
tasks. Retrieval-augmented generation (RAG) systems mitigate this by
incorporating external knowledge sources, such as structured knowledge graphs
(KGs). However, LLMs often struggle to produce accurate answers despite access
to KG-extracted information containing necessary facts. Our study investigates
this dilemma by analyzing error patterns in existing KG-based RAG methods and
identifying eight critical failure points. We observed that these errors
predominantly occur due to insufficient focus on discerning the question's
intent and adequately gathering relevant context from the knowledge graph
facts. Drawing on this analysis, we propose the Mindful-RAG approach, a
framework designed for intent-based and contextually aligned knowledge
retrieval. This method explicitly targets the identified failures and offers
improvements in the correctness and relevance of responses provided by LLMs,
representing a significant step forward from existing methods.
