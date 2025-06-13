---
layout: publication
title: 'Knowledge Graph Tuning: Real-time Large Language Model Personalization Based On Human Feedback'
authors: Jingwei Sun, Zhixu Du, Yiran Chen
conference: "Arxiv"
year: 2024
bibkey: sun2024knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19686"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'RAG', 'GPT', 'Interpretability and Explainability', 'Applications']
---
Large language models (LLMs) have demonstrated remarkable proficiency in a
range of natural language processing tasks. Once deployed, LLMs encounter users
with personalized factual knowledge, and such personalized knowledge is
consistently reflected through users' interactions with the LLMs. To enhance
user experience, real-time model personalization is essential, allowing LLMs to
adapt user-specific knowledge based on user feedback during human-LLM
interactions. Existing methods mostly require back-propagation to finetune the
model parameters, which incurs high computational and memory costs. In
addition, these methods suffer from low interpretability, which will cause
unforeseen impacts on model performance during long-term use, where the user's
personalized knowledge is accumulated extensively.To address these challenges,
we propose Knowledge Graph Tuning (KGT), a novel approach that leverages
knowledge graphs (KGs) to personalize LLMs. KGT extracts personalized factual
knowledge triples from users' queries and feedback and optimizes KGs without
modifying the LLM parameters. Our method improves computational and memory
efficiency by avoiding back-propagation and ensures interpretability by making
the KG adjustments comprehensible to humans.Experiments with state-of-the-art
LLMs, including GPT-2, Llama2, and Llama3, show that KGT significantly improves
personalization performance while reducing latency and GPU memory costs.
Ultimately, KGT offers a promising solution of effective, efficient, and
interpretable real-time LLM personalization during user interactions with the
LLMs.
