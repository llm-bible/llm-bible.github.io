---
layout: publication
title: 'Exploring Rl-based LLM Training For Formal Language Tasks With Programmed Rewards'
authors: Alexander G. Padula, Dennis J. N. J. Soemers
conference: "Arxiv"
year: 2024
bibkey: padula2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.17126"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Reinforcement Learning', 'Training Techniques']
---
Proximal Policy Optimization (PPO) is commonly used in Reinforcement Learning
from Human Feedback to align large language models (LLMs) with downstream
tasks. This paper investigates the feasibility of using PPO for direct
reinforcement learning (RL) from explicitly programmed reward signals, as
opposed to indirect learning from human feedback via an intermediary reward
model. We focus on tasks expressed through formal languages, such as
mathematics and programming, where explicit reward functions can be programmed
to automatically assess the quality of generated outputs. We apply this
approach to a sentiment alignment task, a simple arithmetic task, and a more
complex game synthesis task. The sentiment alignment task replicates prior
research and serves to validate our experimental setup. Our results show that
pure RL-based training for the two formal language tasks is challenging, with
success being limited even for the simple arithmetic task. We propose a novel
batch-entropy regularization term to aid exploration, although training is not
yet entirely stable. Our findings suggest that direct RL training of LLMs may
be more suitable for relatively minor changes, such as alignment, than for
learning new tasks altogether, even if an informative reward signal can be
expressed programmatically.
