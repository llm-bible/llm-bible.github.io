---
layout: publication
title: Bird-Eye Transformers for Text Generation Models
authors: Sha Lei, Song Yuhang, Yordanov Yordan, Salvatori Tommaso, Lukasiewicz Thomas
conference: "Arxiv"
year: 2022
bibkey: sha2022bird
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.03985"}
  - {name: "Code", url: "https://sites.google.com/view/bet-transformer/home}"}
tags: ['ARXIV', 'Attention Mechanism', 'Ethics And Bias', 'Has Code', 'Language Modeling', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Transformers have become an indispensable module for text generation models since their great success in machine translation. Previous works attribute the~success of transformers to the query-key-value dot-product attention which provides a robust inductive bias by the fully connected token graphs. However we found that self-attention has a severe limitation. When predicting the (i+1)-th token self-attention only takes the i-th token as an information collector and it tends to give a high attention weight to those tokens similar to itself. Therefore most of the historical information that occurred before the i-th token is not taken into consideration. Based on this observation in this paper we propose a new architecture called bird-eye transformer(BET) which goes one step further to improve the performance of transformers by reweighting self-attention to encourage it to focus more on important historical information. We have conducted experiments on multiple text generation tasks including machine translation (2 datasets) and language models (3 datasets). These experimental~results show that our proposed model achieves a better performance than the baseline transformer architectures on~all~datasets. The code is released at urlhttps://sites.google.com/view/bet-transformer/home}.
