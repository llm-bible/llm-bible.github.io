---
layout: publication
title: Training Generative Question45;answering On Synthetic Data Obtained From An Instruct45;tuned Model
authors: Takahashi Kosuke, Omi Takahiro, Arima Kosuke, Ishigaki Tatsuya
conference: "Arxiv"
year: 2023
bibkey: takahashi2023training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08072"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Training Techniques']
---
This paper presents a simple and cost45;effective method for synthesizing data to train question45;answering systems. For training fine45;tuning GPT models is a common practice in resource45;rich languages like English however it becomes challenging for non45;English languages due to the scarcity of sufficient question45;answer (QA) pairs. Existing approaches use question and answer generators trained on human45;authored QA pairs which involves substantial human expenses. In contrast we use an instruct45;tuned model to generate QA pairs in a zero45;shot or few45;shot manner. We conduct experiments to compare various strategies for obtaining QA pairs from the instruct45;tuned model. The results demonstrate that a model trained on our proposed synthetic data achieves comparable performance to a model trained on manually curated datasets without incurring human costs.
