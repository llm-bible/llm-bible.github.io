---
layout: publication
title: 'Probing-rag: Self-probing To Guide Language Models In Selective Document Retrieval'
authors: Ingeol Baek, Hwan Chang, Byeongjeong Kim, Jimin Lee, Hwanhee Lee
conference: "Arxiv"
year: 2024
bibkey: baek2024probing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13339"}
tags: ['RAG', 'Reinforcement Learning']
---
Retrieval-Augmented Generation (RAG) enhances language models by retrieving
and incorporating relevant external knowledge. However, traditional
retrieve-and-generate processes may not be optimized for real-world scenarios,
where queries might require multiple retrieval steps or none at all. In this
paper, we propose a Probing-RAG, which utilizes the hidden state
representations from the intermediate layers of language models to adaptively
determine the necessity of additional retrievals for a given query. By
employing a pre-trained prober, Probing-RAG effectively captures the model's
internal cognition, enabling reliable decision-making about retrieving external
documents. Experimental results across five open-domain QA datasets demonstrate
that Probing-RAG outperforms previous methods while reducing the number of
redundant retrieval steps.
