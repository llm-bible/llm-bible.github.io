---
layout: publication
title: 'Auto-intent: Automated Intent Discovery And Self-exploration For Large Language Model Web Agents'
authors: Jaekyeom Kim, Dong-ki Kim, Lajanugen Logeswaran, Sungryull Sohn, Honglak Lee
conference: "Arxiv"
year: 2024
bibkey: kim2024auto
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.22552'}
tags: ['Agentic', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'GPT', 'Reinforcement Learning', 'Pretraining Methods']
---
In this paper, we introduce Auto-Intent, a method to adapt a pre-trained
large language model (LLM) as an agent for a target domain without direct
fine-tuning, where we empirically focus on web navigation tasks. Our approach
first discovers the underlying intents from target domain demonstrations
unsupervisedly, in a highly compact form (up to three words). With the
extracted intents, we train our intent predictor to predict the next intent
given the agent's past observations and actions. In particular, we propose a
self-exploration approach where top-k probable intent predictions are provided
as a hint to the pre-trained LLM agent, which leads to enhanced decision-making
capabilities. Auto-Intent substantially improves the performance of GPT-\{3.5,
4\} and Llama-3.1-\{70B, 405B\} agents on the large-scale real-website navigation
benchmarks from Mind2Web and online navigation tasks from WebArena with its
cross-benchmark generalization from Mind2Web.
