---
layout: publication
title: "Outliers Dimensions That Disrupt Transformers Are Driven By Frequency"
authors: Puccetti Giovanni, Rogers Anna, Drozd Aleksandr, Dell'orletta Felice
conference: "Arxiv"
year: 2022
bibkey: puccetti2022outliers
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.11380"}
tags: ['Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
While Transformer-based language models are generally very robust to pruning there is the recently discovered outlier phenomenon disabling only 48 out of 110M parameters in BERT-base drops its performance by nearly 3037; on MNLI. We replicate the original evidence for the outlier phenomenon and we link it to the geometry of the embedding space. We find that in both BERT and RoBERTa the magnitude of hidden state coefficients corresponding to outlier dimensions correlates with the frequency of encoded tokens in pre-training data and it also contributes to the vertical self-attention pattern enabling the model to focus on the special tokens. This explains the drop in performance from disabling the outliers and it suggests that to decrease anisotropicity in future models we need pre-training schemas that would better take into account the skewed token distributions.
