---
layout: publication
title: 'Fine-tuning Large Language Models For Multigenerator, Multidomain, And Multilingual Machine-generated Text Detection'
authors: Feng Xiong, Thanet Markchom, Ziwei Zheng, Subin Jung, Varun Ojha, Huizhi Liang
conference: "Arxiv"
year: 2024
bibkey: xiong2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.12326"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'BERT', 'Transformer', 'Fine-Tuning']
---
SemEval-2024 Task 8 introduces the challenge of identifying machine-generated
texts from diverse Large Language Models (LLMs) in various languages and
domains. The task comprises three subtasks: binary classification in
monolingual and multilingual (Subtask A), multi-class classification (Subtask
B), and mixed text detection (Subtask C). This paper focuses on Subtask A & B.
Each subtask is supported by three datasets for training, development, and
testing. To tackle this task, two methods: 1) using traditional machine
learning (ML) with natural language preprocessing (NLP) for feature extraction,
and 2) fine-tuning LLMs for text classification. The results show that
transformer models, particularly LoRA-RoBERTa, exceed traditional ML methods in
effectiveness, with majority voting being particularly effective in
multilingual contexts for identifying machine-generated texts.
