---
layout: publication
title: "A Comparative Study Of DSL Code Generation: Fine-tuning Vs. Optimized Retrieval Augmentation"
authors: Bassamzadeh Nastaran, Methani Chhaya
conference: "Arxiv"
year: 2024
bibkey: bassamzadeh2024comparative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02742"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
Natural Language to Code Generation has made significant progress in recent years with the advent of Large Language Models(LLMs). While generation for general-purpose languages like C C++ and Python has improved significantly LLMs struggle with custom function names in Domain Specific Languages or DSLs. This leads to higher hallucination rates and syntax errors specially for DSLs having a high number of custom function names. Additionally constant updates to function names add to the challenge as LLMs need to stay up-to-date. In this paper we present optimizations for using Retrieval Augmented Generation (or RAG) with LLMs for DSL generation along with an ablation study comparing these strategies. We generated a train as well as test dataset with a DSL to represent automation tasks across roughly 700 APIs in public domain. We used the training dataset to fine-tune a Codex model for this DSL. Our results showed that the fine-tuned model scored the best on code similarity metric. With our RAG optimizations we achieved parity for similarity metric. The compilation rate however showed that both the models still got the syntax wrong many times with RAG-based method being 2 pts better. Conversely hallucination rate for RAG model lagged by 1 pt for API names and by 2 pts for API parameter keys. We conclude that an optimized RAG model can match the quality of fine-tuned models and offer advantages for new unseen APIs.
