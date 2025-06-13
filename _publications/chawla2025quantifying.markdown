---
layout: publication
title: 'Quantifying The Importance Of Data Alignment In Downstream Model Performance'
authors: Krrish Chawla, Aryan Sahai, Mario Depavia, Sudharsan Sundar, Brando Miranda
conference: "ICLR DMLR Data-centric Machine Learning Research (2024)"
year: 2025
bibkey: chawla2025quantifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.08496"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training']
---
Contrary to the conventional emphasis on dataset size, we explore the role of
data alignment -- an often overlooked aspect of data quality -- in training
capable Large Language Models (LLMs). To do so, we use the Task2Vec-based
alignment coefficient, a quantitative measure of the similarity between two
datasets, to quantify the impact of alignment between training data and
evaluation data on downstream performance. In particular, we conduct controlled
\textit\{interventional\} experiments for two settings: 1. the impact of
increased alignment coefficients between various pre-training (pt) against
evaluation datasets, and 2. the impact of increased alignment coefficients
between domain specific fine-tuning (ft) against domain specific evaluation.
The domain specific task we explore is Autoformalization -- the machine
translation task between natural language and code for formal verification. In
both settings, we find a strong, predictable negative correlation between the
alignment coefficient of a model's training and evaluation data and the model's
loss/perplexity on the respective downstream task. These findings suggest a
re-evaluation of LLM training approaches, demonstrating the relevance of data
alignment compared to data quantity, especially in specialized downstream tasks
such as Autoformalization.
