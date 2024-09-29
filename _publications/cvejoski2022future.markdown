---
layout: publication
title: The future is different Large pre-trained language models fail in prediction tasks
authors: Cvejoski Kostadin, Sánchez Ramsés J., Ojeda César
conference: "Arxiv"
year: 2022
bibkey: cvejoski2022future
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.00384"}
tags: ['Attention Mechanism', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Large pre-trained language models (LPLM) have shown spectacular success when fine-tuned on downstream supervised tasks. Yet it is known that their performance can drastically drop when there is a distribution shift between the data used during training and that used at inference time. In this paper we focus on data distributions that naturally change over time and introduce four new REDDIT datasets namely the WALLSTREETBETS ASKSCIENCE THE DONALD and POLITICS sub-reddits. First we empirically demonstrate that LPLM can display average performance drops of about 88 (in the best case!) when predicting the popularity of future posts from sub-reddits whose topic distribution changes with time. We then introduce a simple methodology that leverages neural variational dynamic topic models and attention mechanisms to infer temporal language model representations for regression tasks. Our models display performance drops of only about 40 in the worst cases (2 in the best ones) when predicting the popularity of future posts while using only about 7 of the total number of parameters of LPLM and providing interpretable representations that offer insight into real-world events like the GameStop short squeeze of 2021
