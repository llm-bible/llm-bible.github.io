---
layout: publication
title: Joint Copying And Restricted Generation For Paraphrase
authors: Cao Ziqiang, Luo Chuwei, Li Wenjie, Li Sujian
conference: "Arxiv"
year: 2016
bibkey: cao2016joint
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1611.09235"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Training Techniques']
---
Many natural language generation tasks such as abstractive summarization and text simplification are paraphrase45;orientated. In these tasks copying and rewriting are two main writing modes. Most previous sequence45;to45;sequence (Seq2Seq) models use a single decoder and neglect this fact. In this paper we develop a novel Seq2Seq model to fuse a copying decoder and a restricted generative decoder. The copying decoder finds the position to be copied based on a typical attention model. The generative decoder produces words limited in the source45;specific vocabulary. To combine the two decoders and determine the final output we develop a predictor to predict the mode of copying or rewriting. This predictor can be guided by the actual writing mode in the training data. We conduct extensive experiments on two different paraphrase datasets. The result shows that our model outperforms the state45;of45;the45;art approaches in terms of both informativeness and language quality.
