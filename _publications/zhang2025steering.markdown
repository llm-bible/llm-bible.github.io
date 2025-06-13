---
layout: publication
title: 'SAGE: Steering And Refining Dialog Generation With State-action Augmentation'
authors: Yizhe Zhang, Navdeep Jaitly
conference: "Arxiv"
year: 2025
bibkey: zhang2025steering
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.03040'}
tags: ['Agentic', 'RAG', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent advances in large language models have demonstrated impressive
capabilities in task-oriented applications, yet building emotionally
intelligent chatbots that can engage in natural, strategic conversations
remains a challenge. We present a novel approach called SAGE that uses latent
variables to control long-horizon behavior in dialogue generation. At the core
of our method is the State-Action Chain (SAC), which augments standard language
model fine-tuning by introducing latent variables that encapsulate emotional
states and conversational strategies between dialogue turns. During inference,
these variables are generated before each response, enabling coarse-grained
control over dialogue progression while maintaining natural interaction
patterns. We also introduce a self-improvement pipeline that leverages dialogue
tree search, LLM-based reward modeling, and targeted fine-tuning to optimize
conversational trajectories. Our experimental results show that models trained
with this approach demonstrate improved performance in emotional intelligence
metrics while maintaining strong capabilities on LLM benchmarks. The discrete
nature of our latent variables facilitates search-based strategies and provides
a foundation for future applications of reinforcement learning to dialogue
systems, where learning can occur at the state level rather than the token
level.
