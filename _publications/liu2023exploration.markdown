---
layout: publication
title: Exploration With Principles For Diverse AI Supervision
authors: Liu Hao, Zaharia Matei, Abbeel Pieter
conference: "Arxiv"
year: 2023
bibkey: liu2023exploration
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08899"}
tags: ['Agentic', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Training large transformers using next-token prediction has given rise to groundbreaking advancements in AI. While this generative AI approach has produced impressive results it heavily leans on human supervision. Even state-of-the-art AI models like ChatGPT depend on fine-tuning through human demonstrations demanding extensive human input and domain expertise. This strong reliance on human oversight poses a significant hurdle to the advancement of AI innovation. To address this limitation we propose a novel paradigm termed Exploratory AI (EAI) aimed at autonomously generating high-quality training data. Drawing inspiration from unsupervised reinforcement learning (RL) pretraining EAI achieves exploration within the natural language space. We accomplish this by harnessing large language models to assess the novelty of generated content. Our approach employs two key components an actor that generates novel content following exploration principles and a critic that evaluates the generated content offering critiques to guide the actor. Empirical evaluations demonstrate that EAI significantly boosts model performance on complex reasoning tasks addressing the limitations of human-intensive supervision.
