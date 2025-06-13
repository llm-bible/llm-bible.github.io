---
layout: publication
title: 'Uncertainty-aware Language Modeling For Selective Question Answering'
authors: Qi Yang, Shreya Ravikumar, Fynn Schmitt-ulms, Satvik Lolla, Ege Demir, Iaroslav Elistratov, Alex Lavaee, Sadhana Lolla, Elaheh Ahmadi, Daniela Rus, Alexander Amini, Alejandro Perez
conference: "Arxiv"
year: 2023
bibkey: yang2023uncertainty
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.15451'}
tags: ['Applications', 'BERT', 'Language Modeling', 'Model Architecture']
---
We present an automatic large language model (LLM) conversion approach that
produces uncertainty-aware LLMs capable of estimating uncertainty with every
prediction. Our approach is model- and data-agnostic, is
computationally-efficient, and does not rely on external models or systems. We
evaluate converted models on the selective question answering setting -- to
answer as many questions as possible while maintaining a given accuracy,
forgoing providing predictions when necessary. As part of our results, we test
BERT and Llama 2 model variants on the SQuAD extractive QA task and the
TruthfulQA generative QA task. We show that using the uncertainty estimates
provided by our approach to selectively answer questions leads to significantly
higher accuracy over directly using model probabilities.
