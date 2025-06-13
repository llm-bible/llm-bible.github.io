---
layout: publication
title: 'Pathologies Of Pre-trained Language Models In Few-shot Fine-tuning'
authors: Hanjie Chen, Guoqing Zheng, Ahmed Hassan Awadallah, Yangfeng Ji
conference: "Arxiv"
year: 2022
bibkey: chen2022pathologies
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2204.08039'}
tags: ['Interpretability and Explainability', 'Few-Shot', 'Model Architecture', 'BERT', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods']
---
Although adapting pre-trained language models with few examples has shown
promising performance on text classification, there is a lack of understanding
of where the performance gain comes from. In this work, we propose to answer
this question by interpreting the adaptation behavior using post-hoc
explanations from model predictions. By modeling feature statistics of
explanations, we discover that (1) without fine-tuning, pre-trained models
(e.g. BERT and RoBERTa) show strong prediction bias across labels; (2) although
few-shot fine-tuning can mitigate the prediction bias and demonstrate promising
prediction performance, our analysis shows models gain performance improvement
by capturing non-task-related features (e.g. stop words) or shallow data
patterns (e.g. lexical overlaps). These observations alert that pursuing model
performance with fewer examples may incur pathological prediction behavior,
which requires further sanity check on model predictions and careful design in
model evaluations in few-shot fine-tuning.
