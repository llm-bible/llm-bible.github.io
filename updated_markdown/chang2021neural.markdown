---
layout: publication
title: 'Neural Data-to-text Generation With Lm-based Text Augmentation'
authors: Ernie Chang, Xiaoyu Shen, Dawei Zhu, Vera Demberg, Hui Su
conference: "Arxiv"
year: 2021
citations: 40
bibkey: chang2021neural
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2102.03556'}
tags: ['Language Modeling', 'ACL', 'Few-Shot', 'Training Techniques', 'Model Architecture', 'GPT', 'Applications', 'TACL']
---
For many new application domains for data-to-text generation, the main
obstacle in training neural models consists of a lack of training data. While
usually large numbers of instances are available on the data side, often only
very few text samples are available. To address this problem, we here propose a
novel few-shot approach for this setting. Our approach automatically augments
the data available for training by (i) generating new text samples based on
replacing specific values by alternative ones from the same category, (ii)
generating new text samples based on GPT-2, and (iii) proposing an automatic
method for pairing the new text samples with data samples. As the text
augmentation can introduce noise to the training data, we use cycle consistency
as an objective, in order to make sure that a given data sample can be
correctly reconstructed after having been formulated as text (and that text
samples can be reconstructed from data). On both the E2E and WebNLG benchmarks,
we show that this weakly supervised training paradigm is able to outperform
fully supervised seq2seq models with less than 10% annotations. By utilizing
all annotated data, our model can boost the performance of a standard seq2seq
model by over 5 BLEU points, establishing a new state-of-the-art on both
datasets.
