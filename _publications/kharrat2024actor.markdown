---
layout: publication
title: 'ACING: Actor-critic For Instruction Learning In Black-box Large Language Models'
authors: Salma Kharrat, Fares Fourati, Marco Canini
conference: "Arxiv"
year: 2024
bibkey: kharrat2024actor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.12736"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
The effectiveness of Large Language Models (LLMs) in solving tasks vastly
depends on the quality of the instructions, which often require fine-tuning
through extensive human effort. This highlights the need for automated
instruction optimization; however, this optimization is particularly
challenging when dealing with black-box LLMs, where model parameters and
gradients remain inaccessible. We propose ACING, a task-specific prompt
optimization approach framed as a stateless continuous-action Reinforcement
Learning (RL) problem, known as the continuum bandit setting. ACING leverages
an actor-critic-based method to optimize prompts, learning from
non-differentiable reward signals. We validate ACING by optimizing prompts for
ChatGPT on 30 instruction-based tasks. ACING consistently outperforms baseline
methods, achieving a median score improvement of 10 percentage points.
Furthermore, ACING not only recovers but also surpasses human-crafted expert
instructions, achieving up to a 39 percentage point improvement against human
benchmarks.
