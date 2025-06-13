---
layout: publication
title: 'Memory-efficient Stochastic Methods For Memory-based Transformers'
authors: Vishwajit Kumar Vishnu, C. Chandra Sekhar
conference: "Arxiv"
year: 2023
bibkey: vishnu2023memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08123"}
tags: ['Transformer', 'Efficiency and Optimization', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'BERT']
---
Training Memory-based transformers can require a large amount of memory and
can be quite inefficient. We propose a novel two-phase training mechanism and a
novel regularization technique to improve the training efficiency of
memory-based transformers, which are often used for long-range context
problems. For our experiments, we consider transformer-XL as our baseline model
which is one of memorybased transformer models. We show that our resultant
model, Skip Cross-head TransformerXL, outperforms the baseline on character
level language modeling task with similar parameters and outperforms the
baseline on word level language modelling task with almost 20% fewer
parameters. Our proposed methods do not require any additional memory. We also
demonstrate the effectiveness of our regularization mechanism on BERT which
shows similar performance with reduction in standard deviation of scores of
around 30% on multiple GLUE tasks.
