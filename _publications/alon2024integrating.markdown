---
layout: publication
title: 'Integrating Large Language Models And Reinforcement Learning For Non-linear Reasoning'
authors: Yoav Alon, Cristina David
conference: "Arxiv"
year: 2024
bibkey: alon2024integrating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.13501'}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Reinforcement Learning']
---
Large Language Models (LLMs) were shown to struggle with long-term planning,
which may be caused by the limited way in which they explore the space of
possible solutions. We propose an architecture where a Reinforcement Learning
(RL) Agent guides an LLM's space exploration: (1) the Agent has access to
domain-specific information, and can therefore make decisions about the quality
of candidate solutions based on specific and relevant metrics, which were not
explicitly considered by the LLM's training objective; (2) the LLM can focus on
generating immediate next steps, without the need for long-term planning. We
allow non-linear reasoning by exploring alternative paths and backtracking. We
evaluate this architecture on the program equivalence task, and compare it
against Chain of Thought (CoT) and Tree of Thoughts (ToT). We assess both the
downstream task, denoting the binary classification, and the intermediate
reasoning steps. Our approach compares positively against CoT and ToT.
