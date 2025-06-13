---
layout: publication
title: 'Assessing How Hyperparameters Impact Large Language Models'' Sarcasm Detection Performance'
authors: Montgomery Gole, Andriy Miranskyy
conference: "Arxiv"
year: 2025
bibkey: gole2025assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.06166"}
tags: ['Fine-Tuning', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
Sarcasm detection is challenging for both humans and machines. This work
explores how model characteristics impact sarcasm detection in OpenAI's GPT,
and Meta's Llama-2 models, given their strong natural language understanding,
and popularity. We evaluate fine-tuned and zero-shot models across various
sizes, releases, and hyperparameters. Experiments were conducted on the
political and balanced (pol-bal) portion of the popular Self-Annotated Reddit
Corpus (SARC2.0) sarcasm dataset. Fine-tuned performance improves monotonically
with model size within a model family, while hyperparameter tuning also impacts
performance. In the fine-tuning scenario, full precision Llama-2-13b achieves
state-of-the-art accuracy and \\(F_1\\)-score, both measured at 0.83, comparable to
average human performance. In the zero-shot setting, one GPT-4 model achieves
competitive performance to prior attempts, yielding an accuracy of 0.70 and an
\\(F_1\\)-score of 0.75. Furthermore, a model's performance may increase or decline
with each release, highlighting the need to reassess performance after each
release.
