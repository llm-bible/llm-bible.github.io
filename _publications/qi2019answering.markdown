---
layout: publication
title: Answering Complex Open45;domain Questions Through Iterative Query Generation
authors: Qi Peng, Lin Xiaowen, Mehr Leo, Wang Zijian, Manning Christopher D.
conference: "Arxiv"
year: 2019
bibkey: qi2019answering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.07000"}
tags: ['Applications', 'BERT', 'Interpretability And Explainability', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
It is challenging for current one45;step retrieve45;and45;read question answering (QA) systems to answer questions like Which novel by the author of Armada will be adapted as a feature film by Steven Spielberg because the question seldom contains retrievable clues about the missing entity (here the author). Answering such a question requires multi45;hop reasoning where one must gather information about the missing entity (or facts) to proceed with further reasoning. We present GoldEn (Gold Entity) Retriever which iterates between reading context and retrieving more supporting documents to answer open45;domain multi45;hop questions. Instead of using opaque and computationally expensive neural retrieval models GoldEn Retriever generates natural language search queries given the question and available context and leverages off45;the45;shelf information retrieval systems to query for missing entities. This allows GoldEn Retriever to scale up efficiently for open45;domain multi45;hop reasoning while maintaining interpretability. We evaluate GoldEn Retriever on the recently proposed open45;domain multi45;hop QA dataset HotpotQA and demonstrate that it outperforms the best previously published model despite not using pretrained language models such as BERT.
