---
layout: publication
title: 'Effective Cross-task Transfer Learning For Explainable Natural Language Inference With T5'
authors: Bigoulaeva Irina, Sachdeva Rachneet, Madabushi Harish Tayyar, Villavicencio Aline, Gurevych Iryna
conference: "Arxiv"
year: 2022
bibkey: bigoulaeva2022effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.17301"}
tags: ['Fine Tuning', 'Interpretability And Explainability', 'Pretraining Methods', 'Training Techniques']
---
We compare sequential fine-tuning with a model for multi-task learning in the context where we are interested in boosting performance on two tasks, one of which depends on the other. We test these models on the FigLang2022 shared task which requires participants to predict language inference labels on figurative language along with corresponding textual explanations of the inference predictions. Our results show that while sequential multi-task learning can be tuned to be good at the first of two target tasks, it performs less well on the second and additionally struggles with overfitting. Our findings show that simple sequential fine-tuning of text-to-text models is an extraordinarily powerful method for cross-task knowledge transfer while simultaneously predicting multiple interdependent targets. So much so, that our best model achieved the (tied) highest score on the task.
