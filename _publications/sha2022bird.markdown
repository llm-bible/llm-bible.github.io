---
layout: publication
title: Bird45;eye Transformers For Text Generation Models
authors: Sha Lei, Song Yuhang, Yordanov Yordan, Salvatori Tommaso, Lukasiewicz Thomas
conference: "Arxiv"
year: 2022
bibkey: sha2022bird
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.03985"}
  - {name: "Code", url: "https://sites.google.com/view/bet&#45;transformer/home&#125;"}
tags: ['Applications', 'Attention Mechanism', 'Ethics And Bias', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Transformers have become an indispensable module for text generation models since their great success in machine translation. Previous works attribute the~success of transformers to the query45;key45;value dot45;product attention which provides a robust inductive bias by the fully connected token graphs. However we found that self45;attention has a severe limitation. When predicting the (i+1)45;th token self45;attention only takes the i45;th token as an information collector and it tends to give a high attention weight to those tokens similar to itself. Therefore most of the historical information that occurred before the i45;th token is not taken into consideration. Based on this observation in this paper we propose a new architecture called bird45;eye transformer(BET) which goes one step further to improve the performance of transformers by reweighting self45;attention to encourage it to focus more on important historical information. We have conducted experiments on multiple text generation tasks including machine translation (2 datasets) and language models (3 datasets). These experimental~results show that our proposed model achieves a better performance than the baseline transformer architectures on~all~datasets. The code is released at url123;https://sites.google.com/view/bet&#45;transformer/home&#125;.
