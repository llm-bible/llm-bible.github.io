---
layout: publication
title: 'Ensemw2s: Can An Ensemble Of Llms Be Leveraged To Obtain A Stronger LLM?'
authors: Aakriti Agrawal, Mucong Ding, Zora Che, Chenghao Deng, Anirudh Satheesh, John Langford, Furong Huang
conference: "Arxiv"
year: 2024
bibkey: agrawal2024can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.04571'}
tags: ['Reinforcement Learning', 'RAG', 'Tools']
---
How can we harness the collective capabilities of multiple Large Language
Models (LLMs) to create an even more powerful model? This question forms the
foundation of our research, where we propose an innovative approach to
weak-to-strong (w2s) generalization-a critical problem in AI alignment. Our
work introduces an easy-to-hard (e2h) framework for studying the feasibility of
w2s generalization, where weak models trained on simpler tasks collaboratively
supervise stronger models on more complex tasks. This setup mirrors real-world
challenges, where direct human supervision is limited. To achieve this, we
develop a novel AdaBoost-inspired ensemble method, demonstrating that an
ensemble of weak supervisors can enhance the performance of stronger LLMs
across classification and generative tasks on difficult QA datasets. In several
cases, our ensemble approach matches the performance of models trained on
ground-truth data, establishing a new benchmark for w2s generalization. We
observe an improvement of up to 14% over existing baselines and average
improvements of 5% and 4% for binary classification and generative tasks,
respectively. This research points to a promising direction for enhancing AI
through collective supervision, especially in scenarios where labeled data is
sparse or insufficient.
