---
layout: publication
title: 'Token Dropping For Efficient BERT Pretraining'
authors: Le Hou, Richard Yuanzhe Pang, Tianyi Zhou, Yuexin Wu, Xinying Song, Xiaodan Song, Denny Zhou
conference: "Arxiv"
year: 2022
bibkey: hou2022token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.13240"}
tags: ['Masked Language Model', 'Training Techniques', 'Model Architecture', 'RAG', 'Language Modeling', 'Pretraining Methods', 'BERT', 'Transformer', 'Fine-Tuning']
---
Transformer-based models generally allocate the same amount of computation
for each token in a given sequence. We develop a simple but effective "token
dropping" method to accelerate the pretraining of transformer models, such as
BERT, without degrading its performance on downstream tasks. In short, we drop
unimportant tokens starting from an intermediate layer in the model to make the
model focus on important tokens; the dropped tokens are later picked up by the
last layer of the model so that the model still produces full-length sequences.
We leverage the already built-in masked language modeling (MLM) loss to
identify unimportant tokens with practically no computational overhead. In our
experiments, this simple approach reduces the pretraining cost of BERT by 25%
while achieving similar overall fine-tuning performance on standard downstream
tasks.
