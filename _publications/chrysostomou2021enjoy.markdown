---
layout: publication
title: Enjoy The Salience\: Towards Better Transformer-based Faithful Explanations With Word Salience
authors: Chrysostomou George, Aletras Nikolaos
conference: "Arxiv"
year: 2021
bibkey: chrysostomou2021enjoy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.13759"}
tags: ['Attention Mechanism', 'BERT', 'Fine Tuning', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Pretrained transformer-based models such as BERT have demonstrated state-of-the-art predictive performance when adapted into a range of natural language processing tasks. An open problem is how to improve the faithfulness of explanations (rationales) for the predictions of these models. In this paper we hypothesize that salient information extracted a priori from the training data can complement the task-specific information learned by the model during fine-tuning on a downstream task. In this way we aim to help BERT not to forget assigning importance to informative input tokens when making predictions by proposing SaLoss; an auxiliary loss function for guiding the multi-head attention mechanism during training to be close to salient information extracted a priori using TextRank. Experiments for explanation faithfulness across five datasets show that models trained with SaLoss consistently provide more faithful explanations across four different feature attribution methods compared to vanilla BERT. Using the rationales extracted from vanilla BERT and SaLoss models to train inherently faithful classifiers we further show that the latter result in higher predictive performance in downstream tasks.
