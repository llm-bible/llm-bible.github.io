---
layout: publication
title: 'Syntax-enhanced Pre-trained Model'
authors: Zenan Xu, Daya Guo, Duyu Tang, Qinliang Su, Linjun Shou, Ming Gong, Wanjun Zhong, Xiaojun Quan, Nan Duan, Daxin Jiang
conference: "Arxiv"
year: 2020
bibkey: xu2020syntax
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2012.14116"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Transformer', 'Pre-Training', 'Applications', 'Attention Mechanism']
---
We study the problem of leveraging the syntactic structure of text to enhance
pre-trained models such as BERT and RoBERTa. Existing methods utilize syntax of
text either in the pre-training stage or in the fine-tuning stage, so that they
suffer from discrepancy between the two stages. Such a problem would lead to
the necessity of having human-annotated syntactic information, which limits the
application of existing methods to broader scenarios. To address this, we
present a model that utilizes the syntax of text in both pre-training and
fine-tuning stages. Our model is based on Transformer with a syntax-aware
attention layer that considers the dependency tree of the text. We further
introduce a new pre-training task of predicting the syntactic distance among
tokens in the dependency tree. We evaluate the model on three downstream tasks,
including relation classification, entity typing, and question answering.
Results show that our model achieves state-of-the-art performance on six public
benchmark datasets. We have two major findings. First, we demonstrate that
infusing automatically produced syntax of text improves pre-trained models.
Second, global syntactic distances among tokens bring larger performance gains
compared to local head relations between contiguous tokens.
