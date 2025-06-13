---
layout: publication
title: 'Bidirectional Attention Flow For Machine Comprehension'
authors: Minjoon Seo, Aniruddha Kembhavi, Ali Farhadi, Hannaneh Hajishirzi
conference: "Arxiv"
year: 2016
bibkey: seo2016bidirectional
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1611.01603"}
tags: ['Transformer', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism']
---
Machine comprehension (MC), answering a query about a given context
paragraph, requires modeling complex interactions between the context and the
query. Recently, attention mechanisms have been successfully extended to MC.
Typically these methods use attention to focus on a small portion of the
context and summarize it with a fixed-size vector, couple attentions
temporally, and/or often form a uni-directional attention. In this paper we
introduce the Bi-Directional Attention Flow (BIDAF) network, a multi-stage
hierarchical process that represents the context at different levels of
granularity and uses bi-directional attention flow mechanism to obtain a
query-aware context representation without early summarization. Our
experimental evaluations show that our model achieves the state-of-the-art
results in Stanford Question Answering Dataset (SQuAD) and CNN/DailyMail cloze
test.
