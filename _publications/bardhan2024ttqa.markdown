---
layout: publication
title: 'TTQA-RS- A Break-down Prompting Approach For Multi-hop Table-text Question Answering With Reasoning And Summarization'
authors: Jayetri Bardhan, Bushi Xiao, Daisy Zhe Wang
conference: "Arxiv"
year: 2024
bibkey: bardhan2024ttqa
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14732"}
tags: ['RAG', 'Training Techniques', 'Prompting', 'Applications']
---
Question answering (QA) over tables and text has gained much popularity over
the years. Multi-hop table-text QA requires multiple hops between the table and
text, making it a challenging QA task. Although several works have attempted to
solve the table-text QA task, most involve training the models and requiring
labeled data. In this paper, we have proposed a Retrieval Augmented Generation
(RAG) based model - TTQA-RS: A break-down prompting approach for Multi-hop
Table-Text Question Answering with Reasoning and Summarization. Our model uses
an enhanced retriever for table-text information retrieval and uses augmented
knowledge, including table-text summary with decomposed sub-questions with
answers for a reasoning-based table-text QA. Using open-source language models,
our model outperformed all existing prompting methods for table-text QA tasks
on existing table-text QA datasets, such as HybridQA and OTT-QA's development
set. Our experiments demonstrate the potential of prompt-based approaches using
open-source LLMs. Additionally, by using LLaMA3-70B, our model achieved
state-of-the-art performance for prompting-based methods on multi-hop
table-text QA.
