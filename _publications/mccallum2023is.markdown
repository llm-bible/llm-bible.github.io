---
layout: publication
title: 'Is Feedback All You Need? Leveraging Natural Language Feedback In Goal-conditioned Reinforcement Learning'
authors: Mccallum Sabrina, Taylor-davies Max, Albrecht Stefano V., Suglia Alessandro
conference: "Arxiv"
year: 2023
bibkey: mccallum2023is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.04736"}
tags: ['Agentic', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Despite numerous successes, the field of reinforcement learning (RL) remains
far from matching the impressive generalisation power of human behaviour
learning. One possible way to help bridge this gap be to provide RL agents with
richer, more human-like feedback expressed in natural language. To investigate
this idea, we first extend BabyAI to automatically generate language feedback
from the environment dynamics and goal condition success. Then, we modify the
Decision Transformer architecture to take advantage of this additional signal.
We find that training with language feedback either in place of or in addition
to the return-to-go or goal descriptions improves agents' generalisation
performance, and that agents can benefit from feedback even when this is only
available during training, but not at inference.
