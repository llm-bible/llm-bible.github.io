---
layout: publication
title: 'The Art Of Tool Interface Design'
authors: Yunnan Wu, Paul Chen, Deshank Baranwal, Jinlong Zhou, Jian Yuan
conference: "Arxiv"
year: 2025
bibkey: wu2025art
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.21036'}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Model Architecture', 'Fine-Tuning', 'GPT', 'Prompting', 'Pretraining Methods']
---
We present an agentic framework, Thinker, which achieves state of art
performance in challenging reasoning tasks for realistic customer service
scenarios that involve complex business logic and human interactions via long
horizons. On the \\(\tau\\)-bench retail dataset, Thinker achieves 82.6% success
rate with GPT-4o (version 2024-06-01) (baseline: 68.3%), and 81.9% success
rate with Llama-3.1 405B (baseline: 49.6%), without any fine-tuning. Thinker
effectively closes the gap in reasoning capabilities between the base models by
introducing proper structure.
  The key features of the Thinker framework are: (1) State-Machine Augmented
Generation (SMAG), which represents business logic as state machines and the
LLM uses state machines as tools. (2) Delegation of tasks from the main
reasoning loop to LLM-powered tools. (3) Adaptive context management.
  Our prompting-only solution achieves signficant gains, while still
maintaining a standard agentic architecture with a ReAct style reasoning loop.
The key is to innovate on the tool interface design, as exemplified by SMAG and
the LLM-powered tools.
