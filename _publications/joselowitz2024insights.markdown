---
layout: publication
title: 'Insights From The Inverse: Reconstructing LLM Training Goals Through Inverse Reinforcement Learning'
authors: Jared Joselowitz, Ritam Majumdar, Arjun Jagota, Matthieu Bou, Nyal Patel, Satyapriya Krishna, Sonali Parbhoo
conference: "Arxiv"
year: 2024
bibkey: joselowitz2024insights
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.12491'}
tags: ['Reinforcement Learning', 'Agentic', 'Interpretability and Explainability', 'Training Techniques']
---
Large language models (LLMs) trained with Reinforcement Learning from Human
Feedback (RLHF) have demonstrated remarkable capabilities, but their underlying
reward functions and decision-making processes remain opaque. This paper
introduces a novel approach to interpreting LLMs by applying inverse
reinforcement learning (IRL) to recover their implicit reward functions. We
conduct experiments on toxicity-aligned LLMs of varying sizes, extracting
reward models that achieve up to 85% accuracy in predicting human preferences.
Our analysis reveals key insights into the non-identifiability of reward
functions, the relationship between model size and interpretability, and
potential pitfalls in the RLHF process. We demonstrate that IRL-derived reward
models can be used to fine-tune new LLMs, resulting in comparable or improved
performance on toxicity benchmarks. This work provides a new lens for
understanding and improving LLM alignment, with implications for the
responsible development and deployment of these powerful systems.
