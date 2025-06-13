---
layout: publication
title: 'Conversational Topic Recommendation In Counseling And Psychotherapy With Decision Transformer And Large Language Models'
authors: Aylin Gunal, Baihan Lin, Djallel Bouneffouf
conference: "Arxiv"
year: 2024
bibkey: gunal2024conversational
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.05060'}
tags: ['Agentic', 'Transformer', 'RAG', 'Tools', 'Model Architecture', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Given the increasing demand for mental health assistance, artificial
intelligence (AI), particularly large language models (LLMs), may be valuable
for integration into automated clinical support systems. In this work, we
leverage a decision transformer architecture for topic recommendation in
counseling conversations between patients and mental health professionals. The
architecture is utilized for offline reinforcement learning, and we extract
states (dialogue turn embeddings), actions (conversation topics), and rewards
(scores measuring the alignment between patient and therapist) from previous
turns within a conversation to train a decision transformer model. We
demonstrate an improvement over baseline reinforcement learning methods, and
propose a novel system of utilizing our model's output as synthetic labels for
fine-tuning a large language model for the same task. Although our
implementation based on LLaMA-2 7B has mixed results, future work can
undoubtedly build on the design.
