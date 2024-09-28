---
layout: publication
title: LUNA Language Understanding with Number Augmentations on Transformers via Number Plugins and Pre-training
authors: Han Hongwei, Xu Jialiang, Zhou Mengyu, Shao Yijia, Han Shi, Zhang Dongmei
conference: "Arxiv"
year: 2022
bibkey: han2022luna
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.02691"}
tags: ['ARXIV', 'BERT', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'NLP', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques', 'Transformer']
---
Transformers are widely used in NLP tasks. However current approaches to leveraging transformers to understand language expose one weak spot Number understanding. In some scenarios numbers frequently occur especially in semi-structured data like tables. But current approaches to rich-number tasks with transformer-based language models abandon or lose some of the numeracy information - e.g. breaking numbers into sub-word tokens - which leads to many number-related errors. In this paper we propose the LUNA framework which improves the numerical reasoning and calculation capabilities of transformer-based language models. With the number plugin of NumTok and NumBed LUNA represents each number as a whole to model input. With number pre-training including regression loss and model distillation LUNA bridges the gap between number and vocabulary embeddings. To the best of our knowledge this is the first work that explicitly injects numeracy capability into language models using Number Plugins. Besides evaluating toy models on toy tasks we evaluate LUNA on three large-scale transformer models (RoBERTa BERT TabBERT) over three different downstream tasks (TATQA TabFact CrediTrans) and observe the performances of language models are constantly improved by LUNA. The augmented models also improve the official baseline of TAT-QA (EM 50.15 - 59.58) and achieve SOTA performance on CrediTrans (F1 = 86.17).
