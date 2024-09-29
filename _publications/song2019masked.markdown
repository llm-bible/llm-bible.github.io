---
layout: publication
title: MASS Masked Sequence To Sequence Pre45;training For Language Generation
authors: Song Kaitao, Tan Xu, Qin Tao, Lu Jianfeng, Liu Tie-yan
conference: "Arxiv"
year: 2019
bibkey: song2019masked
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1905.02450"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Language Modeling', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Pre45;training and fine45;tuning e.g. BERT have achieved great success in language understanding by transferring knowledge from rich45;resource pre45;training task to the low/zero45;resource downstream tasks. Inspired by the success of BERT we propose MAsked Sequence to Sequence pre45;training (MASS) for the encoder45;decoder based language generation tasks. MASS adopts the encoder45;decoder framework to reconstruct a sentence fragment given the remaining part of the sentence its encoder takes a sentence with randomly masked fragment (several consecutive tokens) as input and its decoder tries to predict this masked fragment. In this way MASS can jointly train the encoder and decoder to develop the capability of representation extraction and language modeling. By further fine45;tuning on a variety of zero/low45;resource language generation tasks including neural machine translation text summarization and conversational response generation (3 tasks and totally 8 datasets) MASS achieves significant improvements over the baselines without pre45;training or with other pre45;training methods. Specially we achieve the state45;of45;the45;art accuracy (37.5 in terms of BLEU score) on the unsupervised English45;French translation even beating the early attention45;based supervised model.
