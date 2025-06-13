---
layout: publication
title: 'EMORL: Ensemble Multi-objective Reinforcement Learning For Efficient And Flexible LLM Fine-tuning'
authors: Lingxiao Kong, Cong Yang, Susanne Neufang, Oya Deniz Beyan, Zeyd Boukhers
conference: "Arxiv"
year: 2025
bibkey: kong2025ensemble
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.02579'}
tags: ['Agentic', 'Interpretability and Explainability', 'RAG', 'Efficiency and Optimization', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Interpretability', 'Pretraining Methods']
---
Recent advances in reinforcement learning (RL) for large language model (LLM)
fine-tuning show promise in addressing multi-objective tasks but still face
significant challenges, including complex objective balancing, low training
efficiency, poor scalability, and limited explainability. Leveraging ensemble
learning principles, we introduce an Ensemble Multi-Objective RL (EMORL)
framework that fine-tunes multiple models with individual objectives while
optimizing their aggregation after the training to improve efficiency and
flexibility. Our method is the first to aggregate the last hidden states of
individual models, incorporating contextual information from multiple
objectives. This approach is supported by a hierarchical grid search algorithm
that identifies optimal weighted combinations. We evaluate EMORL on counselor
reflection generation tasks, using text-scoring LLMs to evaluate the
generations and provide rewards during RL fine-tuning. Through comprehensive
experiments on the PAIR and Psych8k datasets, we demonstrate the advantages of
EMORL against existing baselines: significantly lower and more stable training
consumption (\\(17,529\pm 1,650\\) data points and \\(6,573\pm 147.43\\) seconds),
improved scalability and explainability, and comparable performance across
multiple objectives.
