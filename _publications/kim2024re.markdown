---
layout: publication
title: RE-RAG Improving Open-Domain QA Performance and Interpretability with Relevance Estimator in Retrieval-Augmented Generation
authors: Kim Kiseung, Lee Jay-yoon
conference: "Arxiv"
year: 2024
bibkey: kim2024re
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05794"}
tags: ['Applications', 'Interpretability And Explainability', 'RAG', 'Tools', 'Training Techniques']
---
The Retrieval Augmented Generation (RAG) framework utilizes a combination of parametric knowledge and external knowledge to demonstrate state-of-the-art performance on open-domain question answering tasks. However the RAG framework suffers from performance degradation when the query is accompanied by irrelevant contexts. In this work we propose the RE-RAG framework which introduces a relevance estimator (RE) that not only provides relative relevance between contexts as previous rerankers did but also provides confidence which can be used to classify whether given context is useful for answering the given question. We propose a weakly supervised method for training the RE simply utilizing question-answer data without any labels for correct contexts. We show that RE trained with a small generator (sLM) can not only improve the sLM fine-tuned together with RE but also improve previously unreferenced large language models (LLMs). Furthermore we investigate new decoding strategies that utilize the proposed confidence measured by RE such as choosing to let the user know that it is unanswerable to answer the question given the retrieved contexts or choosing to rely on LLMs parametric knowledge rather than unrelated contexts.
