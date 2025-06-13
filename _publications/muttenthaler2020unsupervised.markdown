---
layout: publication
title: 'Unsupervised Evaluation For Question Answering With Transformers'
authors: Lukas Muttenthaler, Isabelle Augenstein, Johannes Bjerva
conference: "Arxiv"
year: 2020
bibkey: muttenthaler2020unsupervised
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.03222"}
tags: ['Transformer', 'Pretraining Methods', 'Model Architecture', 'Applications']
---
It is challenging to automatically evaluate the answer of a QA model at
inference time. Although many models provide confidence scores, and simple
heuristics can go a long way towards indicating answer correctness, such
measures are heavily dataset-dependent and are unlikely to generalize. In this
work, we begin by investigating the hidden representations of questions,
answers, and contexts in transformer-based QA architectures. We observe a
consistent pattern in the answer representations, which we show can be used to
automatically evaluate whether or not a predicted answer span is correct. Our
method does not require any labeled data and outperforms strong heuristic
baselines, across 2 datasets and 7 domains. We are able to predict whether or
not a model's answer is correct with 91.37% accuracy on SQuAD, and 80.7%
accuracy on SubjQA. We expect that this method will have broad applications,
e.g., in the semi-automatic development of QA datasets
