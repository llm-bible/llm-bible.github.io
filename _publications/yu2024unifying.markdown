---
layout: publication
title: Rankrag Unifying Context Ranking With Retrieval45;augmented Generation In Llms
authors: Yu Yue, Ping Wei, Liu Zihan, Wang Boxin, You Jiaxuan, Zhang Chao, Shoeybi Mohammad, Catanzaro Bryan
conference: "Arxiv"
year: 2024
bibkey: yu2024unifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02485"}
tags: ['GPT', 'Model Architecture', 'RAG', 'Tools', 'Training Techniques']
---
Large language models (LLMs) typically utilize the top45;k contexts from a retriever in retrieval45;augmented generation (RAG). In this work we propose a novel instruction fine45;tuning framework RankRAG which instruction45;tunes a single LLM for the dual purpose of context ranking and answer generation in RAG. In particular the instruction45;tuned LLMs work surprisingly well by adding a small fraction of ranking data into the training blend and outperform existing expert ranking models including the same LLM exclusively fine45;tuned on a large amount of ranking data. For generation we compare our model with many strong baselines including GPT45;445;0613 GPT45;445;turbo45;202445;0409 and ChatQA45;1.5 an open45;sourced model with the state45;of45;the45;art performance on RAG benchmarks. Specifically our Llama345;RankRAG significantly outperforms Llama345;ChatQA45;1.5 and GPT45;4 models on nine knowledge45;intensive benchmarks. In addition it also performs comparably to GPT45;4 on five RAG benchmarks in the biomedical domain without instruction fine45;tuning on biomedical data demonstrating its superb capability for generalization to new domains.
