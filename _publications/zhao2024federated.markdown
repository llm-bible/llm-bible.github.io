---
layout: publication
title: 'A Federated Framework For Llm-based Recommendation'
authors: Jujia Zhao, Wenjie Wang, Chen Xu, See-kiong Ng, Tat-seng Chua
conference: "Arxiv"
year: 2024
bibkey: zhao2024federated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09959"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Training Techniques', 'LREC', 'Pretraining Methods']
---
Large Language Models (LLMs) have empowered generative recommendation systems
through fine-tuning user behavior data. However, utilizing the user data may
pose significant privacy risks, potentially leading to ethical dilemmas and
violations of data protection regulations. To address the privacy concerns,
Federated Learning for Recommendation (Fed4Rec) has been identified as a
promising solution. However, directly applying Fed4Rec in the LLM context
introduces two challenges: 1) exacerbated client performance imbalance, which
ultimately impacts the system's long-term effectiveness, and 2) substantial
client resource costs, posing a high demand for clients' both computational and
storage capability to locally train and infer LLMs.
  To tackle these challenges, we propose a federated framework for LLM-based
recommendation (shorted as FELLRec). Generally, FELLRec designs two key
strategies. 1) Dynamic balance strategy, which designs dynamic parameter
aggregation and learning speed for different clients, aiming to ensure balanced
performance across clients. 2) Flexible storage strategy, which selectively
retains certain sensitive LLM layers on the client side, while offloading other
layers to the server, aiming to preserve privacy while saving resources.
Experiment results show that FELLRec can achieve a more balanced client
performance and improved overall performance in a computational and
storage-efficient way while safeguarding user privacy well.
