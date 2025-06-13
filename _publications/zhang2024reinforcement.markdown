---
layout: publication
title: 'Reinforcement Retrieval Leveraging Fine-grained Feedback For Fact Checking News Claims With Black-box LLM'
authors: Xuan Zhang, Wei Gao
conference: "Arxiv"
year: 2024
bibkey: zhang2024reinforcement
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.17283"}
tags: ['RAG', 'Training Techniques', 'Reinforcement Learning']
---
Retrieval-augmented language models have exhibited promising performance
across various areas of natural language processing (NLP), including
fact-critical tasks. However, due to the black-box nature of advanced large
language models (LLMs) and the non-retrieval-oriented supervision signal of
specific tasks, the training of retrieval model faces significant challenges
under the setting of black-box LLM. We propose an approach leveraging
Fine-grained Feedback with Reinforcement Retrieval (FFRR) to enhance
fact-checking on news claims by using black-box LLM. FFRR adopts a two-level
strategy to gather fine-grained feedback from the LLM, which serves as a reward
for optimizing the retrieval policy, by rating the retrieved documents based on
the non-retrieval ground truth of the task. We evaluate our model on two public
datasets for real-world news claim verification, and the results demonstrate
that FFRR achieves significant improvements over strong LLM-enabled and non-LLM
baselines.
