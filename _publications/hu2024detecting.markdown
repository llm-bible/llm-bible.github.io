---
layout: publication
title: LRP4RAG&#58; Detecting Hallucinations In Retrieval-augmented Generation Via Layer-wise Relevance Propagation
authors: Hu Haichuan, Sun Yuhan, Zhang Quanjun
conference: "Arxiv"
year: 2024
bibkey: hu2024detecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15533"}
tags: ['RAG']
---
Retrieval-Augmented Generation (RAG) has become a primary technique for mitigating hallucinations in large language models (LLMs). However incomplete knowledge extraction and insufficient understanding can still mislead LLMs to produce irrelevant or even contradictory responses which means hallucinations persist in RAG. In this paper we propose LRP4RAG a method based on the Layer-wise Relevance Propagation (LRP) algorithm for detecting hallucinations in RAG. Specifically we first utilize LRP to compute the relevance between the input and output of the RAG generator. We then apply further extraction and resampling to the relevance matrix. The processed relevance data are input into multiple classifiers to determine whether the output contains hallucinations. To the best of our knowledge this is the first time that LRP has been used for detecting RAG hallucinations and extensive experiments demonstrate that LRP4RAG outperforms existing baselines.
