---
layout: publication
title: 'Quebec Automobile Insurance Question-answering With Retrieval-augmented Generation'
authors: David Beauchemin, Zachary Gagnon, Ricahrd Khoury
conference: "Arxiv"
year: 2024
bibkey: beauchemin2024quebec
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.09623"}
tags: ['RAG', 'GPT', 'Model Architecture', 'Applications']
---
Large Language Models (LLMs) perform outstandingly in various downstream
tasks, and the use of the Retrieval-Augmented Generation (RAG) architecture has
been shown to improve performance for legal question answering (Nuruzzaman and
Hussain, 2020; Louis et al., 2024). However, there are limited applications in
insurance questions-answering, a specific type of legal document. This paper
introduces two corpora: the Quebec Automobile Insurance Expertise Reference
Corpus and a set of 82 Expert Answers to Layperson Automobile Insurance
Questions. Our study leverages both corpora to automatically and manually
assess a GPT4-o, a state-of-the-art LLM, to answer Quebec automobile insurance
questions. Our results demonstrate that, on average, using our expertise
reference corpus generates better responses on both automatic and manual
evaluation metrics. However, they also highlight that LLM QA is unreliable
enough for mass utilization in critical areas. Indeed, our results show that
between 5% to 13% of answered questions include a false statement that could
lead to customer misunderstanding.
