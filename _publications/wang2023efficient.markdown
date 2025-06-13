---
layout: publication
title: 'BERT4CTR: An Efficient Framework To Combine Pre-trained Language Model With Non-textual Features For CTR Prediction'
authors: Dong Wang, Kavé Salamatian, Yunqing Xia, Weiwei Deng, Qi Zhiang
conference: "Arxiv"
year: 2023
bibkey: wang2023efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.11527'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Training Techniques', 'Tools', 'Model Architecture', 'Fine-Tuning', 'BERT', 'Pretraining Methods']
---
Although deep pre-trained language models have shown promising benefit in a
large set of industrial scenarios, including Click-Through-Rate (CTR)
prediction, how to integrate pre-trained language models that handle only
textual signals into a prediction pipeline with non-textual features is
challenging.
  Up to now two directions have been explored to integrate multi-modal inputs
in fine-tuning of pre-trained language models. One consists of fusing the
outcome of language models and non-textual features through an aggregation
layer, resulting into ensemble framework, where the cross-information between
textual and non-textual inputs are only learned in the aggregation layer. The
second one consists of splitting non-textual features into fine-grained
fragments and transforming the fragments to new tokens combined with textual
ones, so that they can be fed directly to transformer layers in language
models. However, this approach increases the complexity of the learning and
inference because of the numerous additional tokens.
  To address these limitations, we propose in this work a novel framework
BERT4CTR, with the Uni-Attention mechanism that can benefit from the
interactions between non-textual and textual features while maintaining low
time-costs in training and inference through a dimensionality reduction.
Comprehensive experiments on both public and commercial data demonstrate that
BERT4CTR can outperform significantly the state-of-the-art frameworks to handle
multi-modal inputs and be applicable to CTR prediction.
