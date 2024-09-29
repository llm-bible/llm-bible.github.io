---
layout: publication
title: A Unified Query45;based Generative Model For Question Generation And Question Answering
authors: Song Linfeng, Wang Zhiguo, Hamza Wael
conference: "Arxiv"
year: 2017
bibkey: song2017unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1709.01058"}
tags: ['Agentic', 'Applications', 'Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
We propose a query45;based generative model for solving both tasks of question generation (QG) and question an45; swering (QA). The model follows the classic encoder45; decoder framework. The encoder takes a passage and a query as input then performs query understanding by matching the query with the passage from multiple per45; spectives. The decoder is an attention45;based Long Short Term Memory (LSTM) model with copy and coverage mechanisms. In the QG task a question is generated from the system given the passage and the target answer whereas in the QA task the answer is generated given the question and the passage. During the training stage we leverage a policy45;gradient reinforcement learning algorithm to overcome exposure bias a major prob45; lem resulted from sequence learning with cross45;entropy loss. For the QG task our experiments show higher per45; formances than the state45;of45;the45;art results. When used as additional training data the automatically generated questions even improve the performance of a strong ex45; tractive QA system. In addition our model shows bet45; ter performance than the state45;of45;the45;art baselines of the generative QA task.
