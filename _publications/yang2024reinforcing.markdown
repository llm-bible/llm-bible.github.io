---
layout: publication
title: 'Reinforcing Thinking Through Reasoning-enhanced Reward Models'
authors: Diji Yang, Linda Zeng, Kezhen Chen, Yi Zhang
conference: "Arxiv"
year: 2024
bibkey: yang2024reinforcing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.01457"}
tags: ['Tools', 'Efficiency and Optimization', 'Ethics and Bias', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Distillation']
---
Large Language Models (LLMs) exhibit great potential in complex multi-step
reasoning through inference-time thinking but still struggle with deciding when
to stop thinking due to limited self-awareness about their knowledge
boundaries. While human preference alignment has shown extraordinary
opportunities, expensive labeling challenges adherence to scaling law. Language
model self-critique, as an alternative to using human-labeled reasoning data,
is questioned with its inherited biases. This work addresses these challenges
by distilling the LLM's own reasoning processes into synthetic behavioral data,
eliminating the need for manual labeling of intermediate steps. Building on
this concept, we propose Distillation-Reinforcement-Reasoning (DRR), a
three-step framework that leverages the LLM's inherent behaviors as external
feedback by first generating behavioral data using the Reasoner (LLM) to
reflect its reasoning capabilities, then training a lightweight discriminative
reward model (DM) on behavioral data, and finally deploying the DM at inference
time to assist the Reasoner's decision-making. Experiments on multiple
benchmarks show that the DRR framework outperforms self-critique approaches
without relying on additional complex data annotation. Benefiting from
lightweight design, ease of replication, and adaptability, DRR is applicable to
a wide range of LLM-centric tasks.
