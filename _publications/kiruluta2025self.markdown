---
layout: publication
title: 'A Self-supervised Reinforcement Learning Approach For Fine-tuning Large Language Models Using Cross-attention Signals'
authors: Andrew Kiruluta, Andreas Lemos, Priscilla Burity
conference: "Arxiv"
year: 2025
bibkey: kiruluta2025self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.10482'}
tags: ['Attention Mechanism', 'Agentic', 'RAG', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
We propose a novel reinforcement learning framework for post training large
language models that does not rely on human in the loop feedback. Instead, our
approach uses cross attention signals within the model itself to derive a self
supervised reward, thereby guiding iterative fine tuning of the model policy.
By analyzing how the model attends to the input prompt during generation, we
construct measures of prompt coverage, focus, and coherence. We then use these
measures to rank or score candidate responses, providing a reward signal that
encourages the model to produce well aligned, on topic text. In empirical
comparisons against standard policy gradient methods and RL fine tuning with
synthetic preference models, our method shows significant gains in prompt
relevance and consistency over a non RL baseline. While it does not yet match
the performance of fully human supervised RLHF systems, it highlights an
important direction for scaling alignment with minimal human labeling. We
provide a detailed analysis, discuss potential limitations, and outline future
work for combining cross-attention based signals with smaller amounts of human
feedback.
