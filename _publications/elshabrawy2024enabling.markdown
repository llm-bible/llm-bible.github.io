---
layout: publication
title: 'Enabling Natural Zero-shot Prompting On Encoder Models Via Statement-tuning'
authors: Ahmed Elshabrawy, Yongxin Huang, Iryna Gurevych, Alham Fikri Aji
conference: "Arxiv"
year: 2024
bibkey: elshabrawy2024enabling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.12897"}
tags: ['Masked Language Model', 'Training Techniques', 'Model Architecture', 'Few-Shot', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Prompting']
---
While Large Language Models (LLMs) exhibit remarkable capabilities in
zero-shot and few-shot scenarios, they often require computationally
prohibitive sizes. Conversely, smaller Masked Language Models (MLMs) like BERT
and RoBERTa achieve state-of-the-art results through fine-tuning but struggle
with extending to few-shot and zero-shot settings due to their architectural
constraints. Hence, we propose Statement-Tuning, a technique that models
discriminative tasks as a set of finite statements and trains an encoder model
to discriminate between the potential statements to determine the label. We do
Statement-Tuning on multiple tasks to enable cross-task generalization.
Experimental results demonstrate that Statement-Tuning achieves competitive
performance compared to state-of-the-art LLMs with significantly fewer
parameters. Moreover, the study investigates the impact of several design
choices on few-shot and zero-shot generalization, revealing that
Statement-Tuning can achieve strong performance with modest training data and
benefits from task and statement diversity for unseen task generalizability.
