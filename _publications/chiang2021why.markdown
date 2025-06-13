---
layout: publication
title: 'Why Can You Lay Off Heads? Investigating How BERT Heads Transfer'
authors: Ting-rui Chiang, Yun-nung Chen
conference: "Arxiv"
year: 2021
bibkey: chiang2021why
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.07137"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Distillation', 'Pretraining Methods', 'BERT', 'Transformer', 'Fine-Tuning']
---
The huge size of the widely used BERT family models has led to recent efforts
about model distillation. The main goal of distillation is to create a
task-agnostic pre-trained model that can be fine-tuned on downstream tasks
without fine-tuning its full-sized version. Despite the progress of
distillation, to what degree and for what reason a task-agnostic model can be
created from distillation has not been well studied. Also, the mechanisms
behind transfer learning of those BERT models are not well investigated either.
Therefore, this work focuses on analyzing the acceptable deduction when
distillation for guiding the future distillation procedure. Specifically, we
first inspect the prunability of the Transformer heads in RoBERTa and ALBERT
using their head importance estimation proposed by Michel et al. (2019), and
then check the coherence of the important heads between the pre-trained task
and downstream tasks. Hence, the acceptable deduction of performance on the
pre-trained task when distilling a model can be derived from the results, and
we further compare the behavior of the pruned model before and after
fine-tuning. Our studies provide guidance for future directions about BERT
family model distillation.
