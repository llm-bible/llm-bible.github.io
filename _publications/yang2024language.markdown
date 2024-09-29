---
layout: publication
title: (text)memory^3 Language Modeling With Explicit Memory
authors: Yang Hongkang, Lin Zehao, Wang Wenjin, Wu Hao, Li Zhiyu, Tang Bo, Wei Wenqiang, Wang Jinbo, Tang Zeyun, Song Shichao, Xi Chenyang, Yu Yu, Chen Kai, Xiong Feiyu, Tang Linpeng, E Weinan
conference: "Arxiv"
year: 2024
bibkey: yang2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01178"}
tags: ['Language Modeling', 'Pretraining Methods', 'Pruning', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
The training and inference of large language models (LLMs) are together a costly process that transports knowledge from raw data to meaningful computation. Inspired by the memory hierarchy of the human brain we reduce this cost by equipping LLMs with explicit memory a memory format cheaper than model parameters and text retrieval-augmented generation (RAG). Conceptually with most of its knowledge externalized to explicit memories the LLM can enjoy a smaller parameter size training cost and inference cost all proportional to the amount of remaining abstract knowledge. As a preliminary proof of concept we train from scratch a 2.4B LLM which achieves better performance than much larger LLMs as well as RAG models and maintains higher decoding speed than RAG. The model is named (textMemory)^3 since explicit memory is the third form of memory in LLMs after implicit memory (model parameters) and working memory (context key-values). We introduce a memory circuitry theory to support the externalization of knowledge and present novel techniques including a memory sparsification mechanism that makes storage tractable and a two-stage pretraining scheme that facilitates memory formation.
