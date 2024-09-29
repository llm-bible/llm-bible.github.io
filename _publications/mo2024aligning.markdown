---
layout: publication
title: Aligning Query Representation With Rewritten Query And Relevance Judgments In Conversational Search
authors: Mo Fengran, Qu Chen, Mao Kelong, Wu Yihong, Su Zhan, Huang Kaiyu, Nie Jian-yun
conference: "Arxiv"
year: 2024
bibkey: mo2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.20189"}
tags: ['Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Conversational search supports multi45;turn user45;system interactions to solve complex information needs. Different from the traditional single45;turn ad45;hoc search conversational search encounters a more challenging problem of context45;dependent query understanding with the lengthy and long45;tail conversational history context. While conversational query rewriting methods leverage explicit rewritten queries to train a rewriting model to transform the context45;dependent query into a stand45;stone search query this is usually done without considering the quality of search results. Conversational dense retrieval methods use fine45;tuning to improve a pre45;trained ad45;hoc query encoder but they are limited by the conversational search data available for training. In this paper we leverage both rewritten queries and relevance judgments in the conversational search data to train a better query representation model. The key idea is to align the query representation with those of rewritten queries and relevant documents. The proposed model 45;45; Query Representation Alignment Conversational Dense Retriever QRACDR is tested on eight datasets including various settings in conversational search and ad45;hoc search. The results demonstrate the strong performance of QRACDR compared with state45;of45;the45;art methods and confirm the effectiveness of representation alignment.
