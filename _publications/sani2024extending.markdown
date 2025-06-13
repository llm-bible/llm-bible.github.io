---
layout: publication
title: 'Extending Llms To New Languages: A Case Study Of Llama And Persian Adaptation'
authors: Samin Mahdizadeh Sani, Pouya Sadeghi, Thuy-trang Vu, Yadollah Yaghoobzadeh, Gholamreza Haffari
conference: "Arxiv"
year: 2024
bibkey: sani2024extending
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.13375'}
tags: ['Language Modeling', 'Applications', 'Training Techniques', 'Fine-Tuning', 'Pretraining Methods']
---
Large language models (LLMs) have made great progress in classification and
text generation tasks. However, they are mainly trained on English data and
often struggle with low-resource languages. In this study, we explore adding a
new language, i.e., Persian, to Llama (a model with a limited understanding of
Persian) using parameter-efficient fine-tuning. We employ a multi-stage
approach involving pretraining on monolingual Persian data, aligning
representations through bilingual pretraining and instruction datasets, and
instruction-tuning with task-specific datasets. We evaluate the model's
performance at each stage on generation and classification tasks. Our findings
suggest that incorporating the Persian language, through bilingual data
alignment, can enhance classification accuracy for Persian tasks, with no
adverse impact and sometimes even improvements on English tasks. Additionally,
the results highlight the model's initial strength as a critical factor when
working with limited training data, with cross-lingual alignment offering
minimal benefits for the low-resource language. Knowledge transfer from English
to Persian has a marginal effect, primarily benefiting simple classification
tasks.
