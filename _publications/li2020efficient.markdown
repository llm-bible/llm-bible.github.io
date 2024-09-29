---
layout: publication
title: Efficient Transformer45;based Large Scale Language Representations Using Hardware45;friendly Block Structured Pruning
authors: Li Bingbing, Kong Zhenglun, Zhang Tianyun, Li Ji, Li Zhengang, Liu Hang, Ding Caiwen
conference: "Arxiv"
year: 2020
bibkey: li2020efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2009.08065"}
tags: ['BERT', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'RAG', 'Tools', 'Transformer']
---
Pre45;trained large45;scale language models have increasingly demonstrated high accuracy on many natural language processing (NLP) tasks. However the limited weight storage and computational speed on hardware platforms have impeded the popularity of pre45;trained models especially in the era of edge computing. In this work we propose an efficient transformer45;based large45;scale language representation using hardware45;friendly block structure pruning. We incorporate the reweighted group Lasso into block45;structured pruning for optimization. Besides the significantly reduced weight storage and computation the proposed approach achieves high compression rates. Experimental results on different models (BERT RoBERTa and DistilBERT) on the General Language Understanding Evaluation (GLUE) benchmark tasks show that we achieve up to 5.0x with zero or minor accuracy degradation on certain task(s). Our proposed method is also orthogonal to existing compact pre45;trained language models such as DistilBERT using knowledge distillation since a further 1.79x average compression rate can be achieved on top of DistilBERT with zero or minor accuracy degradation. It is suitable to deploy the final compressed model on resource45;constrained edge devices.
