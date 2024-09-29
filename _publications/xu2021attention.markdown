---
layout: publication
title: Attention45;guided Generative Models For Extractive Question Answering
authors: Xu Peng, Liang Davis, Huang Zhiheng, Xiang Bing
conference: "Arxiv"
year: 2021
bibkey: xu2021attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.06393"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
We propose a novel method for applying Transformer models to extractive question answering (QA) tasks. Recently pretrained generative sequence45;to45;sequence (seq2seq) models have achieved great success in question answering. Contributing to the success of these models are internal attention mechanisms such as cross45;attention. We propose a simple strategy to obtain an extractive answer span from the generative model by leveraging the decoder cross45;attention patterns. Viewing cross45;attention as an architectural prior we apply joint training to further improve QA performance. Empirical results show that on open45;domain question answering datasets like NaturalQuestions and TriviaQA our method approaches state45;of45;the45;art performance on both generative and extractive inference all while using much fewer parameters. Furthermore this strategy allows us to perform hallucination45;free inference while conferring significant improvements to the models ability to rerank relevant passages.
