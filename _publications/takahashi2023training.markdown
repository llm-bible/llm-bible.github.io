---
layout: publication
title: "Training Generative Question-answering On Synthetic Data Obtained From An Instruct-tuned Model"
authors: Takahashi Kosuke, Omi Takahiro, Arima Kosuke, Ishigaki Tatsuya
conference: "Arxiv"
year: 2023
bibkey: takahashi2023training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08072"}
tags: ['Few Shot', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
This paper presents a simple and cost-effective method for synthesizing data to train question-answering systems. For training fine-tuning GPT models is a common practice in resource-rich languages like English however it becomes challenging for non-English languages due to the scarcity of sufficient question-answer (QA) pairs. Existing approaches use question and answer generators trained on human-authored QA pairs which involves substantial human expenses. In contrast we use an instruct-tuned model to generate QA pairs in a zero-shot or few-shot manner. We conduct experiments to compare various strategies for obtaining QA pairs from the instruct-tuned model. The results demonstrate that a model trained on our proposed synthetic data achieves comparable performance to a model trained on manually curated datasets without incurring human costs.
