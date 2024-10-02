---
layout: publication
title: 'Abductive Reasoning As Self-supervision For Common Sense Question Answering'
authors: Aakur Sathyanarayanan N., Sarkar Sudeep
conference: "Arxiv"
year: 2019
bibkey: aakur2019abductive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.03099"}
tags: ['Applications', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Question answering has seen significant advances in recent times, especially with the introduction of increasingly bigger transformer-based models pre-trained on massive amounts of data. While achieving impressive results on many benchmarks, their performances appear to be proportional to the amount of training data available in the target domain. In this work, we explore the ability of current question-answering models to generalize - to both other domains as well as with restricted training data. We find that large amounts of training data are necessary, both for pre-training as well as fine-tuning to a task, for the models to perform well on the designated task. We introduce a novel abductive reasoning approach based on Grenander's Pattern Theory framework to provide self-supervised domain adaptation cues or pseudo-labels, which can be used instead of expensive human annotations. The proposed self-supervised training regimen allows for effective domain adaptation without losing performance compared to fully supervised baselines. Extensive experiments on two publicly available benchmarks show the efficacy of the proposed approach. We show that neural networks models trained using self-labeled data can retain up to \(75\%\) of the performance of models trained on large amounts of human-annotated training data.
