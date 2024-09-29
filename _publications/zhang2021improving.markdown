---
layout: publication
title: Improving Stack Overflow Question Title Generation With Copying Enhanced Codebert Model And Bi45;modal Information
authors: Zhang Fengji, Yu Xiao, Keung Jacky, Li Fuyang, Xie Zhiwen, Yang Zhen, Ma Caoyuan, Zhang Zhimin
conference: "Arxiv"
year: 2021
bibkey: zhang2021improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.13073"}
tags: ['Attention Mechanism', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Context Stack Overflow is very helpful for software developers who are seeking answers to programming problems. Previous studies have shown that a growing number of questions are of low quality and thus obtain less attention from potential answerers. Gao et al. proposed an LSTM45;based model (i.e. BiLSTM45;CC) to automatically generate question titles from the code snippets to improve the question quality. However only using the code snippets in the question body cannot provide sufficient information for title generation and LSTMs cannot capture the long45;range dependencies between tokens. Objective This paper proposes CCBERT a deep learning based novel model to enhance the performance of question title generation by making full use of the bi45;modal information of the entire question body. Method CCBERT follows the encoder45;decoder paradigm and uses CodeBERT to encode the question body into hidden representations a stacked Transformer decoder to generate predicted tokens and an additional copy attention layer to refine the output distribution. Both the encoder and decoder perform the multi45;head self45;attention operation to better capture the long45;range dependencies. This paper builds a dataset containing around 200000 high45;quality questions filtered from the data officially published by Stack Overflow to verify the effectiveness of the CCBERT model. Results CCBERT outperforms all the baseline models on the dataset. Experiments on both code45;only and low45;resource datasets show the superiority of CCBERT with less performance degradation. The human evaluation also shows the excellent performance of CCBERT concerning both readability and correlation criteria.
