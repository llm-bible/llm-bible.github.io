---
layout: publication
title: 'Dialogxpert: Driving Intelligent And Emotion-aware Conversations Through Online Value-based Reinforcement Learning With LLM Priors'
authors: Tazeek Bin Abdur Rakib, Ambuj Mehrish, Lay-ki Soon, Wern Han Lim, Soujanya Poria
conference: "Arxiv"
year: 2025
bibkey: rakib2025driving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.17795'}
  - {name: "Code", url: 'https://github.com/declare-lab/dialogxpert/'}
tags: ['Agentic', 'Has Code', 'RAG', 'Model Architecture', 'BERT', 'Tools', 'Reinforcement Learning']
---
Large-language-model (LLM) agents excel at reactive dialogue but struggle with proactive, goal-driven interactions due to myopic decoding and costly planning. We introduce DialogXpert, which leverages a frozen LLM to propose a small, high-quality set of candidate actions per turn and employs a compact Q-network over fixed BERT embeddings trained via temporal-difference learning to select optimal moves within this reduced space. By tracking the user's emotions, DialogXpert tailors each decision to advance the task while nurturing a genuine, empathetic connection. Across negotiation, emotional support, and tutoring benchmarks, DialogXpert drives conversations to under \\(3\\) turns with success rates exceeding 94% and, with a larger LLM prior, pushes success above 97% while markedly improving negotiation outcomes. This framework delivers real-time, strategic, and emotionally intelligent dialogue planning at scale. Code available at https://github.com/declare-lab/dialogxpert/
