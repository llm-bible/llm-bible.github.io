---
layout: publication
title: 'Chatbot Arena Meets Nuggets: Towards Explanations And Diagnostics In The Evaluation Of LLM Responses'
authors: Sahel Sharifymoghaddam, Shivani Upadhyay, Nandan Thakur, Ronak Pradeep, Jimmy Lin
conference: "Arxiv"
year: 2025
bibkey: sharifymoghaddam2025chatbot
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.20006"}
  - {name: "Code", url: "https://github.com/castorini/lmsys_nuggetize"}
tags: ['Tools', 'Interpretability and Explainability', 'RAG', 'Reinforcement Learning', 'Has Code']
---
Battles, or side-by-side comparisons in so-called arenas that elicit human preferences, have emerged as a popular approach for assessing the output quality of LLMs. Recently, this idea has been extended to retrieval-augmented generation (RAG) systems. While undoubtedly representing an advance in evaluation, battles have at least two drawbacks, particularly in the context of complex information-seeking queries: they are neither explanatory nor diagnostic. Recently, the nugget evaluation methodology has emerged as a promising approach to evaluate the quality of RAG answers. Nuggets decompose long-form LLM-generated answers into atomic facts, highlighting important pieces of information necessary in a "good" response. In this work, we apply our AutoNuggetizer framework to analyze data from roughly 7K Search Arena battles provided by LMArena in a fully automatic manner. Our results show a significant correlation between nugget scores and human preferences, showcasing promise in our approach to explainable and diagnostic system evaluations. All the code necessary to reproduce results in our work is available in https://github.com/castorini/lmsys_nuggetize.
