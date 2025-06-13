---
layout: publication
title: 'Grounded Language Agent For Product Search Via Intelligent Web Interactions'
authors: Moghis Fereidouni, Adib Mosharrof, A. B. Siddique
conference: "2024.customnlp4u-1.7"
year: 2024
bibkey: fereidouni2024grounded
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10887"}
  - {name: "Code", url: "https://github.com/MultifacetedNLP/WebAgents-Unsupervised"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Fine-Tuning', 'Has Code', 'Prompting', 'Attention Mechanism']
---
The development of agents powered by large language models (LLMs) to
accomplish complex high-level user intents, has attracted significant attention
recently. However, employing LLMs with billions of parameters (e.g., GPT-4) may
incur substantial costs on top of handcrafting extensive prompts. To address
this, we introduce a Grounded Language Agent for Intelligent Web Interactions,
named GLAINTEL. GLAINTEL employs Flan-T5 as its backbone and is flexible in
training in various settings: unsupervised learning, supervised learning, and
unsupervised domain adaptation. Specifically, we tackle both the challenge of
learning without human demonstrations and the opportunity to leverage human
demonstrations effectively when those are available. Additionally, we explore
unsupervised domain adaptation for cases where demonstrations are limited to a
specific domain. Experimental evaluations across diverse setups demonstrate the
effectiveness of GLAINTEL in unsupervised settings, outperforming in-context
learning-based approaches that employ larger models with up to 540 billion
parameters. Surprisingly, behavioral cloning-based methods that
straightforwardly use human demonstrations do not outperform unsupervised
variants of GLAINTEL. Additionally, we show that combining human demonstrations
with reinforcement learning-based training yields results comparable to methods
utilizing GPT-4. The code is available at:
https://github.com/MultifacetedNLP/WebAgents-Unsupervised.
