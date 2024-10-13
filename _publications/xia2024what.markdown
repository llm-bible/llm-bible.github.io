---
layout: publication
title: 'What To Do If Language Models Disagree? Black-box Model Ensembling For Textual And Visual Question Answering'
authors: Xia Yuxi, Zaporojets Kilm, Roth Benjamin
conference: "Arxiv"
year: 2024
bibkey: xia2024what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12841"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
A diverse range of large language models (LLMs), e.g., ChatGPT, and visual
question answering (VQA) models, e.g., BLIP, have been developed for solving
textual and visual question answering tasks. However, both LLMs and VQA models
encounter challenges when applied to task-specific datasets. Fine-tuning these
models is either difficult, as it requires access via APIs, rendering them as
black-boxes, or costly due to the need of tuning a large number of parameters.
To address this, we introduce InfoSel, a data-efficient and lightweight
ensemble method that learns to dynamically pick the winner from existing
black-box models for predictions on both textual and multimodal visual question
answering tasks. Unlike traditional ensemble models, InfoSel does not rely on
prediction probabilities or confidences, which typically are not available in
black-box models. Experimental results on four datasets demonstrate that our
approach achieves an absolute increase of up to +5.27% in the F1-score compared
to standalone LLMs. Remarkably, this improvement is achieved by utilizing only
1K training instances and 110M model parameters for training task-specific
ensemble models.
