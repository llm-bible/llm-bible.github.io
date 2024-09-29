---
layout: publication
title: Compressing Transformer-Based Semantic Parsing Models using Compositional Code Embeddings
authors: Prakash Prafull, Shashidhar Saurabh Kumar, Zhao Wenlong, Rongali Subendhu, Khan Haidar, Kayser Michael
conference: "Arxiv"
year: 2020
bibkey: prakash2020compressing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.05002"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
The current state-of-the-art task-oriented semantic parsing models use BERT or RoBERTa as pretrained encoders; these models have huge memory footprints. This poses a challenge to their deployment for voice assistants such as Amazon Alexa and Google Assistant on edge devices with limited memory budgets. We propose to learn compositional code embeddings to greatly reduce the sizes of BERT-base and RoBERTa-base. We also apply the technique to DistilBERT ALBERT-base and ALBERT-large three already compressed BERT variants which attain similar state-of-the-art performances on semantic parsing with much smaller model sizes. We observe 95.15 ~ 98.46 embedding compression rates and 20.47 ~ 34.22 encoder compression rates while preserving greater than 97.5 semantic parsing performances. We provide the recipe for training and analyze the trade-off between code embedding sizes and downstream performances.
