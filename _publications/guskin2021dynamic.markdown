---
layout: publication
title: 'Dynamic-tinybert: Boost Tinybert''s Inference Efficiency By Dynamic Sequence Length'
authors: Shira Guskin, Moshe Wasserblat, Ke Ding, Gyuwan Kim
conference: "Arxiv"
year: 2021
bibkey: guskin2021dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2111.09645"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Pretraining Methods', 'BERT', 'Transformer', 'Applications']
---
Limited computational budgets often prevent transformers from being used in
production and from having their high accuracy utilized. TinyBERT addresses the
computational efficiency by self-distilling BERT into a smaller transformer
representation having fewer layers and smaller internal embedding. However,
TinyBERT's performance drops when we reduce the number of layers by 50%, and
drops even more abruptly when we reduce the number of layers by 75% for
advanced NLP tasks such as span question answering. Additionally, a separate
model must be trained for each inference scenario with its distinct
computational budget. In this work we present Dynamic-TinyBERT, a TinyBERT
model that utilizes sequence-length reduction and Hyperparameter Optimization
for enhanced inference efficiency per any computational budget.
Dynamic-TinyBERT is trained only once, performing on-par with BERT and
achieving an accuracy-speedup trade-off superior to any other efficient
approaches (up to 3.3x with <1% loss-drop). Upon publication, the code to
reproduce our work will be open-sourced.
