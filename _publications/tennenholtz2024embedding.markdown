---
layout: publication
title: 'Embedding-aligned Language Models'
authors: Guy Tennenholtz, Yinlam Chow, Chih-wei Hsu, Lior Shani, Ethan Liang, Craig Boutilier
conference: "Arxiv"
year: 2024
bibkey: tennenholtz2024embedding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.00024'}
tags: ['Agentic', 'Language Modeling', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Survey Paper', 'Reinforcement Learning']
---
We propose a novel approach for training large language models (LLMs) to
adhere to objectives defined within a latent embedding space. Our method
leverages reinforcement learning (RL), treating a pre-trained LLM as an
environment. Our embedding-aligned guided language (EAGLE) agent is trained to
iteratively steer the LLM's generation towards optimal regions of the latent
embedding space, w.r.t. some predefined criterion. We demonstrate the
effectiveness of the EAGLE agent using the MovieLens 25M and Amazon Review
datasets to surface content gaps that satisfy latent user demand. We also
demonstrate the benefit of using an optimal design of a state-dependent action
set to improve EAGLE's efficiency. Our work paves the way for controlled and
grounded text generation using LLMs, ensuring consistency with domain-specific
knowledge and data representations.
