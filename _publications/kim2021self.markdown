---
layout: publication
title: 'Self-guided Contrastive Learning For BERT Sentence Representations'
authors: Taeuk Kim, Kang Min Yoo, Sang-goo Lee
conference: "Arxiv"
year: 2021
citations: 66
bibkey: kim2021self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2106.07345'}
tags: ['Transformer', 'Training Techniques', 'BERT', 'Model Architecture', 'Pretraining Methods']
---
Although BERT and its variants have reshaped the NLP landscape, it still
remains unclear how best to derive sentence embeddings from such pre-trained
Transformers. In this work, we propose a contrastive learning method that
utilizes self-guidance for improving the quality of BERT sentence
representations. Our method fine-tunes BERT in a self-supervised fashion, does
not rely on data augmentation, and enables the usual [CLS] token embeddings to
function as sentence vectors. Moreover, we redesign the contrastive learning
objective (NT-Xent) and apply it to sentence representation learning. We
demonstrate with extensive experiments that our approach is more effective than
competitive baselines on diverse sentence-related tasks. We also show it is
efficient at inference and robust to domain shifts.
