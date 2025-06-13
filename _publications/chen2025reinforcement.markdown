---
layout: publication
title: 'Reinforcement Learning For Long-horizon Interactive LLM Agents'
authors: Kevin Chen, Marco Cusumano-towner, Brody Huval, Aleksei Petrenko, Jackson Hamburger, Vladlen Koltun, Philipp Krähenbühl
conference: "Arxiv"
year: 2025
bibkey: chen2025reinforcement
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.01600'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Interactive digital agents (IDAs) leverage APIs of stateful digital
environments to perform tasks in response to user requests. While IDAs powered
by instruction-tuned large language models (LLMs) can react to feedback from
interface invocations in multi-step exchanges, they have not been trained in
their respective digital environments. Prior methods accomplish less than half
of tasks in sophisticated benchmarks such as AppWorld. We present a
reinforcement learning (RL) approach that trains IDAs directly in their target
environments. We formalize this training as a partially observable Markov
decision process and derive LOOP, a data- and memory-efficient variant of
proximal policy optimization. LOOP uses no value network and maintains exactly
one copy of the underlying LLM in memory, making its implementation
straightforward and as memory-efficient as fine-tuning a single LLM. A
32-billion-parameter agent trained with LOOP in the AppWorld environment
outperforms the much larger OpenAI o1 agent by 9 percentage points (15%
relative). To our knowledge, this is the first reported application of RL to
IDAs that interact with a stateful, multi-domain, multi-app environment via
direct API calls. Our analysis sheds light on the effectiveness of RL in this
area, showing that the agent learns to consult the API documentation, avoid
unwarranted assumptions, minimize confabulation, and recover from setbacks.
