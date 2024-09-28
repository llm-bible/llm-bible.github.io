---
layout: publication
title: RecGPT Generative Personalized Prompts for Sequential Recommendation via ChatGPT Training Paradigm
authors: Zhang Yabin, Yu Wenhui, Zhang Erhan, Chen Xu, Hu Lantao, Jiang Peng, Gai Kun
conference: "Arxiv"
year: 2024
bibkey: zhang2024recgpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08675"}
tags: ['ARXIV', 'Chatgpt', 'Fine Tuning', 'GPT', 'PRE Training', 'Prompt', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
ChatGPT has achieved remarkable success in natural language understanding. Considering that recommendation is indeed a conversation between users and the system with items as words which has similar underlying pattern with ChatGPT we design a new chat framework in item index level for the recommendation task. Our novelty mainly contains three parts model training and inference. For the model part we adopt Generative Pre-training Transformer (GPT) as the sequential recommendation model and design a user modular to capture personalized information. For the training part we adopt the two-stage paradigm of ChatGPT including pre-training and fine-tuning. In the pre-training stage we train GPT model by auto-regression. In the fine-tuning stage we train the model with prompts which include both the newly-generated results from the model and the users feedback. For the inference part we predict several user interests as user representations in an autoregressive manner. For each interest vector we recall several items with the highest similarity and merge the items recalled by all interest vectors into the final result. We conduct experiments with both offline public datasets and online A/B test to demonstrate the effectiveness of our proposed method.
