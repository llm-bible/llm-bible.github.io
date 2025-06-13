---
layout: publication
title: 'Reusing Embeddings: Reproducible Reward Model Research In Large Language Model Alignment Without Gpus'
authors: Hao Sun, Yunyi Shen, Jean-francois Ton, Mihaela Van Der Schaar
conference: "Arxiv"
year: 2025
bibkey: sun2025reusing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04357"}
tags: ['Agentic', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have made substantial strides in structured
tasks through Reinforcement Learning (RL), demonstrating proficiency in
mathematical reasoning and code generation. However, applying RL in broader
domains like chatbots and content generation -- through the process known as
Reinforcement Learning from Human Feedback (RLHF) -- presents unique
challenges. Reward models in RLHF are critical, acting as proxies that evaluate
the alignment of LLM outputs with human intent. Despite advancements, the
development of reward models is hindered by challenges such as computational
heavy training, costly evaluation, and therefore poor reproducibility. We
advocate for using embedding-based input in reward model research as an
accelerated solution to those challenges. By leveraging embeddings for reward
modeling, we can enhance reproducibility, reduce computational demands on
hardware, improve training stability, and significantly reduce training and
evaluation costs, hence facilitating fair and efficient comparisons in this
active research area. We then show a case study of reproducing existing reward
model ensemble research using embedding-based reward models. We discussed
future avenues for research, aiming to contribute to safer and more effective
LLM deployments.
