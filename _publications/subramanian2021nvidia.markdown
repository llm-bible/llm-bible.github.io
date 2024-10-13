---
layout: publication
title: 'NVIDIA Nemo Neural Machine Translation Systems For English-german And English-russian News And Biomedical Tasks At WMT21'
authors: Subramanian Sandeep, Hrinchuk Oleksii, Adams Virginia, Kuchaiev Oleksii
conference: "Arxiv"
year: 2021
bibkey: subramanian2021nvidia
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2111.08634"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Ethics And Bias', 'Merging', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Scaling Laws', 'Transformer']
---
This paper provides an overview of NVIDIA NeMo's neural machine translation
systems for the constrained data track of the WMT21 News and Biomedical Shared
Translation Tasks. Our news task submissions for English-German (En-De) and
English-Russian (En-Ru) are built on top of a baseline transformer-based
sequence-to-sequence model. Specifically, we use a combination of 1) checkpoint
averaging 2) model scaling 3) data augmentation with backtranslation and
knowledge distillation from right-to-left factorized models 4) finetuning on
test sets from previous years 5) model ensembling 6) shallow fusion decoding
with transformer language models and 7) noisy channel re-ranking. Additionally,
our biomedical task submission for English-Russian uses a biomedically biased
vocabulary and is trained from scratch on news task data, medically relevant
text curated from the news task dataset, and biomedical data provided by the
shared task. Our news system achieves a sacreBLEU score of 39.5 on the WMT'20
En-De test set outperforming the best submission from last year's task of 38.8.
Our biomedical task Ru-En and En-Ru systems reach BLEU scores of 43.8 and 40.3
respectively on the WMT'20 Biomedical Task Test set, outperforming the previous
year's best submissions.
