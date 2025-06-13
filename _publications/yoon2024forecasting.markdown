---
layout: publication
title: 'Forecasting Live Chat Intent From Browsing History'
authors: Se-eun Yoon, Ahmad Bin Rabiah, Zaid Alibadi, Surya Kallumadi, Julian Mcauley
conference: "Arxiv"
year: 2024
bibkey: yoon2024forecasting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.04668'}
tags: ['Agentic', 'Transformer', 'Model Architecture', 'Pretraining Methods']
---
Customers reach out to online live chat agents with various intents, such as
asking about product details or requesting a return. In this paper, we propose
the problem of predicting user intent from browsing history and address it
through a two-stage approach. The first stage classifies a user's browsing
history into high-level intent categories. Here, we represent each browsing
history as a text sequence of page attributes and use the ground-truth class
labels to fine-tune pretrained Transformers. The second stage provides a large
language model (LLM) with the browsing history and predicted intent class to
generate fine-grained intents. For automatic evaluation, we use a separate LLM
to judge the similarity between generated and ground-truth intents, which
closely aligns with human judgments. Our two-stage approach yields significant
performance gains compared to generating intents without the classification
stage.
