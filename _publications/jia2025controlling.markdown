---
layout: publication
title: 'Controlling Large Language Model With Latent Actions'
authors: Chengxing Jia, Ziniu Li, Pengyuan Wang, Yi-chen Li, Zhenyu Hou, Yuxiao Dong, Yang Yu
conference: "Arxiv"
year: 2025
bibkey: jia2025controlling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.21383"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Language Modeling', 'Fine-Tuning', 'Prompting', 'Applications']
---
Adapting Large Language Models (LLMs) to downstream tasks using Reinforcement
Learning (RL) has proven to be an effective approach. However, LLMs do not
inherently define the structure of an agent for RL training, particularly in
terms of defining the action space. This paper studies learning a compact
latent action space to enhance the controllability and exploration of RL for
LLMs. We propose Controlling Large Language Models with Latent Actions (CoLA),
a framework that integrates a latent action space into pre-trained LLMs. We
apply CoLA to the Llama-3.1-8B model. Our experiments demonstrate that,
compared to RL with token-level actions, CoLA's latent action enables greater
semantic diversity in text generation. For enhancing downstream tasks, we show
that CoLA with RL achieves a score of 42.4 on the math500 benchmark, surpassing
the baseline score of 38.2, and reaches 68.2 when augmented with a Monte Carlo
Tree Search variant. Furthermore, CoLA with RL consistently improves
performance on agent-based tasks without degrading the pre-trained LLM's
capabilities, unlike the baseline. Finally, CoLA reduces computation time by
half in tasks involving enhanced thinking prompts for LLMs by RL. These results
highlight CoLA's potential to advance RL-based adaptation of LLMs for
downstream applications.
