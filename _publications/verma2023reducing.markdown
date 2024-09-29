---
layout: publication
title: "Reducing LLM Hallucinations Using Epistemic Neural Networks"
authors: Verma Shreyas, Tran Kien, Ali Yusuf, Min Guangyu
conference: "Arxiv"
year: 2023
bibkey: verma2023reducing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.15576"}
tags: ['Pretraining Methods', 'RAG']
---
Reducing and detecting hallucinations in large language models is an open research problem. In this project we attempt to leverage recent advances in the field of uncertainty estimation to reduce hallucinations in frozen large language models. Epistemic neural networks have recently been proposed to improve output joint distributions for large pre-trained models. ENNs are small networks attached to large frozen models to improve the models joint distributions and uncertainty estimates. In this work we train an epistemic neural network on top of the Llama-2 7B model combined with a contrastive decoding feature enhancement technique. We are the first to train an ENN for the next token prediction task and explore the efficacy of this method in reducing hallucinations on the TruthfulQA dataset. In essence we provide a method that leverages a pre-trained models latent embeddings to reduce hallucinations.
