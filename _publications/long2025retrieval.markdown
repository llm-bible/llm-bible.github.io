---
layout: publication
title: 'Retrieval-augmented Visual Question Answering Via Built-in Autoregressive Search Engines'
authors: Xinwei Long, Zhiyuan Ma, Ermo Hua, Kaiyan Zhang, Biqing Qi, Bowen Zhou
conference: "Arxiv"
year: 2025
bibkey: long2025retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16641"}
tags: ['RAG', 'GPT', 'Applications', 'Pretraining Methods']
---
Retrieval-augmented generation (RAG) has emerged to address the
knowledge-intensive visual question answering (VQA) task. Current methods
mainly employ separate retrieval and generation modules to acquire external
knowledge and generate answers, respectively. We propose ReAuSE, an alternative
to the previous RAG model for the knowledge-based VQA task, which seamlessly
integrates knowledge retriever into the generative multi-modal large language
model, serving as a built-in search engine. Specifically, our model functions
both as a generative retriever and an accurate answer generator. It not only
helps retrieve documents from the knowledge base by producing identifiers for
each document, but it also answers visual questions based on the retrieved
documents. Furthermore, we propose a reinforced retrieval calibration module
from relevance feedback to improve retrieval performance and align with the
preferences for accurate answer generation. Extensive experiments on two
representative OKVQA and A-OKVQA datasets demonstrate significant improvements
ranging from 2.9% to 9.6% across all evaluation metrics when compared to
strong baselines.
