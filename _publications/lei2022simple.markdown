---
layout: publication
title: 'Simple Recurrence Improves Masked Language Models'
authors: Tao Lei, Ran Tian, Jasmijn Bastings, Ankur P. Parikh
conference: "Arxiv"
year: 2022
bibkey: lei2022simple
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2205.11588'}
tags: ['Masked Language Model', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'BERT', 'Fine-Tuning', 'Pretraining Methods']
---
In this work, we explore whether modeling recurrence into the Transformer
architecture can both be beneficial and efficient, by building an extremely
simple recurrent module into the Transformer. We compare our model to baselines
following the training and evaluation recipe of BERT. Our results confirm that
recurrence can indeed improve Transformer models by a consistent margin,
without requiring low-level performance optimizations, and while keeping the
number of parameters constant. For example, our base model achieves an absolute
improvement of 2.1 points averaged across 10 tasks and also demonstrates
increased stability in fine-tuning over a range of learning rates.
