---
layout: publication
title: 'Aligning Query Representation With Rewritten Query And Relevance Judgments In Conversational Search'
authors: Mo Fengran, Qu Chen, Mao Kelong, Wu Yihong, Su Zhan, Huang Kaiyu, Nie Jian-yun
conference: "Arxiv"
year: 2024
bibkey: mo2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.20189"}
tags: ['Fine Tuning', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Conversational search supports multi-turn user-system interactions to solve complex information needs. Different from the traditional single-turn ad-hoc search conversational search encounters a more challenging problem of context-dependent query understanding with the lengthy and long-tail conversational history context. While conversational query rewriting methods leverage explicit rewritten queries to train a rewriting model to transform the context-dependent query into a stand-stone search query this is usually done without considering the quality of search results. Conversational dense retrieval methods use fine-tuning to improve a pre-trained ad-hoc query encoder but they are limited by the conversational search data available for training. In this paper we leverage both rewritten queries and relevance judgments in the conversational search data to train a better query representation model. The key idea is to align the query representation with those of rewritten queries and relevant documents. The proposed model -- Query Representation Alignment Conversational Dense Retriever QRACDR is tested on eight datasets including various settings in conversational search and ad-hoc search. The results demonstrate the strong performance of QRACDR compared with state-of-the-art methods and confirm the effectiveness of representation alignment.
