---
layout: publication
title: CG-BERT&#58; Conditional Text Generation With BERT For Generalized Few-shot Intent Detection
authors: Xia Congying, Zhang Chenwei, Nguyen Hoang, Zhang Jiawei, Yu Philip
conference: "Arxiv"
year: 2020
bibkey: xia2020cg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.01881"}
tags: ['Applications', 'BERT', 'Few Shot', 'Language Modeling', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
In this paper we formulate a more realistic and difficult problem setup for the intent detection task in natural language understanding namely Generalized Few-Shot Intent Detection (GFSID). GFSID aims to discriminate a joint label space consisting of both existing intents which have enough labeled data and novel intents which only have a few examples for each class. To approach this problem we propose a novel model Conditional Text Generation with BERT (CG-BERT). CG-BERT effectively leverages a large pre-trained language model to generate text conditioned on the intent label. By modeling the utterance distribution with variational inference CG-BERT can generate diverse utterances for the novel intents even with only a few utterances available. Experimental results show that CG-BERT achieves state-of-the-art performance on the GFSID task with 1-shot and 5-shot settings on two real-world datasets.
