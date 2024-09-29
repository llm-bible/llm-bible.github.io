---
layout: publication
title: Knowledge Neurons In Pretrained Transformers
authors: Dai Damai, Dong Li, Hao Yaru, Sui Zhifang, Chang Baobao, Wei Furu
conference: "Arxiv"
year: 2021
bibkey: dai2021knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2104.08696"}
  - {name: "Code", url: "https://github.com/Hunter&#45;DDM/knowledge&#45;neurons"}
tags: ['BERT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Large45;scale pretrained language models are surprisingly good at recalling factual knowledge presented in the training corpus. In this paper we present preliminary studies on how factual knowledge is stored in pretrained Transformers by introducing the concept of knowledge neurons. Specifically we examine the fill45;in45;the45;blank cloze task for BERT. Given a relational fact we propose a knowledge attribution method to identify the neurons that express the fact. We find that the activation of such knowledge neurons is positively correlated to the expression of their corresponding facts. In our case studies we attempt to leverage knowledge neurons to edit (such as update and erase) specific factual knowledge without fine45;tuning. Our results shed light on understanding the storage of knowledge within pretrained Transformers. The code is available at https://github.com/Hunter&#45;DDM/knowledge&#45;neurons.
