---
layout: publication
title: ProphetNet Predicting Future N-gram for Sequence-to-Sequence Pre-training
authors: Qi Weizhen, Yan Yu, Gong Yeyun, Liu Dayiheng, Duan Nan, Chen Jiusheng, Zhang Ruofei, Zhou Ming
conference: "Arxiv"
year: 2020
bibkey: qi2020prophetnet
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2001.04063"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'RAG', 'Training Techniques', 'Transformer']
---
This paper presents a new sequence-to-sequence pre-training model called ProphetNet which introduces a novel self-supervised objective named future n-gram prediction and the proposed n-stream self-attention mechanism. Instead of optimizing one-step-ahead prediction in the traditional sequence-to-sequence model the ProphetNet is optimized by n-step ahead prediction that predicts the next n tokens simultaneously based on previous context tokens at each time step. The future n-gram prediction explicitly encourages the model to plan for the future tokens and prevent overfitting on strong local correlations. We pre-train ProphetNet using a base scale dataset (16GB) and a large-scale dataset (160GB) respectively. Then we conduct experiments on CNN/DailyMail Gigaword and SQuAD 1.1 benchmarks for abstractive summarization and question generation tasks. Experimental results show that ProphetNet achieves new state-of-the-art results on all these datasets compared to the models using the same scale pre-training corpus.
