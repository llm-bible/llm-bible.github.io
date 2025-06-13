---
layout: publication
title: 'Barthez: A Skilled Pretrained French Sequence-to-sequence Model'
authors: Moussa Kamal Eddine, Antoine J. -p. Tixier, Michalis Vazirgiannis
conference: "Arxiv"
year: 2020
bibkey: eddine2020skilled
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.12321"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Applications']
---
Inductive transfer learning has taken the entire NLP field by storm, with
models such as BERT and BART setting new state of the art on countless NLU
tasks. However, most of the available models and research have been conducted
for English. In this work, we introduce BARThez, the first large-scale
pretrained seq2seq model for French. Being based on BART, BARThez is
particularly well-suited for generative tasks. We evaluate BARThez on five
discriminative tasks from the FLUE benchmark and two generative tasks from a
novel summarization dataset, OrangeSum, that we created for this research. We
show BARThez to be very competitive with state-of-the-art BERT-based French
language models such as CamemBERT and FlauBERT. We also continue the
pretraining of a multilingual BART on BARThez' corpus, and show our resulting
model, mBARThez, to significantly boost BARThez' generative performance. Code,
data and models are publicly available.
