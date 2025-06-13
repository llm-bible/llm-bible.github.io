---
layout: publication
title: 'Information Association For Language Model Updating By Mitigating Lm-logical Discrepancy'
authors: Pengfei Yu, Heng Ji
conference: "Arxiv"
year: 2023
bibkey: yu2023information
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.18582"}
tags: ['Fine-Tuning', 'Pre-Training', 'Efficiency and Optimization', 'Language Modeling', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'Distillation']
---
Large Language Models~(LLMs) struggle with providing current information due
to the outdated pre-training data. Existing methods for updating LLMs, such as
knowledge editing and continual fine-tuning, have significant drawbacks in
generalizability of new information and the requirements on structured updating
corpus. We identify the core challenge behind these drawbacks: the LM-logical
discrepancy featuring the difference between language modeling probabilities
and logical probabilities. To evaluate and address the core challenge, we
propose a new task formulation of the information updating task that only
requires the provision of an unstructured updating corpus and evaluates the
performance of information updating on the generalizability to question-answer
pairs pertaining to the updating information. We further propose a novel and
effective pipeline approach for the task, highlighting a self-prompting-based
question-answer generation process and a associative distillation methods to
bridge the LM-logical discrepancy. We develop two datasets for evaluation, one
sourced from news articles published in March and April 2023, and the other
from the Natural Questions benchmark. Experimental results demonstrate the
superiority of our approach, significantly increasing the factual consistency
score (on a scale from 0 to 1) by up to 0.16. Furthermore, our method
effectively mitigates forgetting utilizing a compact replay buffer with only
2.3% of the training tokens.
