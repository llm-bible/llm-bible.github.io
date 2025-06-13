---
layout: publication
title: 'Dependency Learning For Legal Judgment Prediction With A Unified Text-to-text Transformer'
authors: Yunyun Huang, Xiaoyu Shen, Chuanyi Li, Jidong Ge, Bin Luo
conference: "Arxiv"
year: 2021
bibkey: huang2021dependency
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2112.06370'}
tags: ['Masked Language Model', 'Interpretability and Explainability', 'Transformer', 'RAG', 'Training Techniques', 'Model Architecture', 'BERT', 'Prompting', 'Pretraining Methods']
---
Given the fact of a case, Legal Judgment Prediction (LJP) involves a series
of sub-tasks such as predicting violated law articles, charges and term of
penalty. We propose leveraging a unified text-to-text Transformer for LJP,
where the dependencies among sub-tasks can be naturally established within the
auto-regressive decoder. Compared with previous works, it has three advantages:
(1) it fits in the pretraining pattern of masked language models, and thereby
can benefit from the semantic prompts of each sub-task rather than treating
them as atomic labels, (2) it utilizes a single unified architecture, enabling
full parameter sharing across all sub-tasks, and (3) it can incorporate both
classification and generative sub-tasks. We show that this unified transformer,
albeit pretrained on general-domain text, outperforms pretrained models
tailored specifically for the legal domain. Through an extensive set of
experiments, we find that the best order to capture dependencies is different
from human intuitions, and the most reasonable logical order for humans can be
sub-optimal for the model. We further include two more auxiliary tasks: court
view generation and article content prediction, showing they can not only
improve the prediction accuracy, but also provide interpretable explanations
for model outputs even when an error is made. With the best configuration, our
model outperforms both previous SOTA and a single-tasked version of the unified
transformer by a large margin.
