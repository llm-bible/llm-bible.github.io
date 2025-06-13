---
layout: publication
title: 'Towards Bandit-based Prompt-tuning For In-the-wild Foundation Agents'
authors: Finn Rietz, Oleg Smirnov, Sara Karimi, Lele Cao
conference: "Arxiv"
year: 2025
bibkey: rietz2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.06358"}
tags: ['Agentic', 'Model Architecture', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Prompting', 'Pre-Training']
---
Prompting has emerged as the dominant paradigm for adapting large,
pre-trained transformer-based models to downstream tasks. The Prompting
Decision Transformer (PDT) enables large-scale, multi-task offline
reinforcement learning pre-training by leveraging stochastic trajectory prompts
to identify the target task. However, these prompts are sampled uniformly from
expert demonstrations, overlooking a critical limitation: Not all prompts are
equally informative for differentiating between tasks. To address this, we
propose an inference time bandit-based prompt-tuning framework that explores
and optimizes trajectory prompt selection to enhance task performance. Our
experiments indicate not only clear performance gains due to bandit-based
prompt-tuning, but also better sample complexity, scalability, and prompt space
exploration compared to prompt-tuning baselines.
