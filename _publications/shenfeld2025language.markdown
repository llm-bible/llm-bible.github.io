---
layout: publication
title: 'Language Model Personalization Via Reward Factorization'
authors: Idan Shenfeld, Felix Faltings, Pulkit Agrawal, Aldo Pacchiano
conference: "Arxiv"
year: 2025
bibkey: shenfeld2025language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.06358"}
tags: ['Agentic', 'GPT', 'Tools', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Modern large language models (LLMs) are optimized for human-aligned responses
using Reinforcement Learning from Human Feedback (RLHF). However, existing RLHF
approaches assume a universal preference model and fail to account for
individual user preferences, limiting their effectiveness in personalized
applications. We introduce a framework that extends RLHF to enable user
personalization by leveraging the assumption that user preferences lie in a
low-dimensional space. Instead of training a separate model per user, we
represent user-specific rewards as a linear combination of base reward
functions. Using only ~10 user responses, our method can infer user-specific
rewards and align LLM outputs accordingly. We validate our approach through
experiments with both synthetic and real users, demonstrating significant
personalization achieved by our method. In human evaluations, our method
achieves a 67% win rate over default GPT-4o responses.
