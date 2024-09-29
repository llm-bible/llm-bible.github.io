---
layout: publication
title: Prophetnet Predicting Future N45;gram For Sequence45;to45;sequence Pre45;training
authors: Qi Weizhen, Yan Yu, Gong Yeyun, Liu Dayiheng, Duan Nan, Chen Jiusheng, Zhang Ruofei, Zhou Ming
conference: "Arxiv"
year: 2020
bibkey: qi2020predicting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2001.04063"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'RAG', 'Training Techniques', 'Transformer']
---
This paper presents a new sequence45;to45;sequence pre45;training model called ProphetNet which introduces a novel self45;supervised objective named future n45;gram prediction and the proposed n45;stream self45;attention mechanism. Instead of optimizing one45;step45;ahead prediction in the traditional sequence45;to45;sequence model the ProphetNet is optimized by n45;step ahead prediction that predicts the next n tokens simultaneously based on previous context tokens at each time step. The future n45;gram prediction explicitly encourages the model to plan for the future tokens and prevent overfitting on strong local correlations. We pre45;train ProphetNet using a base scale dataset (16GB) and a large45;scale dataset (160GB) respectively. Then we conduct experiments on CNN/DailyMail Gigaword and SQuAD 1.1 benchmarks for abstractive summarization and question generation tasks. Experimental results show that ProphetNet achieves new state45;of45;the45;art results on all these datasets compared to the models using the same scale pre45;training corpus.
