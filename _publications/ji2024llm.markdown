---
layout: publication
title: 'LLM Internal States Reveal Hallucination Risk Faced With A Query'
authors: Ji Ziwei, Chen Delong, Ishii Etsuko, Cahyawijaya Samuel, Bang Yejin, Wilie Bryan, Fung Pascale
conference: "Arxiv"
year: 2024
bibkey: ji2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.03282"}
tags: ['Applications', 'RAG', 'Training Techniques']
---
The hallucination problem of Large Language Models (LLMs) significantly limits their reliability and trustworthiness. Humans have a self-awareness process that allows us to recognize what we dont know when faced with queries. Inspired by this our paper investigates whether LLMs can estimate their own hallucination risk before response generation. We analyze the internal mechanisms of LLMs broadly both in terms of training data sources and across 15 diverse Natural Language Generation (NLG) tasks spanning over 700 datasets. Our empirical analysis reveals two key insights (1) LLM internal states indicate whether they have seen the query in training data or not; and (2) LLM internal states show they are likely to hallucinate or not regarding the query. Our study explores particular neurons activation layers and tokens that play a crucial role in the LLM perception of uncertainty and hallucination risk. By a probing estimator we leverage LLM self-assessment achieving an average hallucination estimation accuracy of 84.3237; at run time.
