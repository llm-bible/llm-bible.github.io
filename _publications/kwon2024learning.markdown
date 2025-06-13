---
layout: publication
title: 'GDPO: Learning To Directly Align Language Models With Diversity Using Gflownets'
authors: Oh Joon Kwon, Daiki E. Matsunaga, Kee-eung Kim
conference: "EMNLP 2024"
year: 2024
bibkey: kwon2024learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.15096'}
tags: ['Agentic', 'Efficiency and Optimization', 'Applications', 'Reinforcement Learning', 'Ethics and Bias']
---
A critical component of the current generation of language models is
preference alignment, which aims to precisely control the model's behavior to
meet human needs and values. The most notable among such methods is
Reinforcement Learning with Human Feedback (RLHF) and its offline variant
Direct Preference Optimization (DPO), both of which seek to maximize a reward
model based on human preferences. In particular, DPO derives reward signals
directly from the offline preference data, but in doing so overfits the reward
signals and generates suboptimal responses that may contain human biases in the
dataset. In this work, we propose a practical application of a
diversity-seeking RL algorithm called GFlowNet-DPO (GDPO) in an offline
preference alignment setting to curtail such challenges. Empirical results show
GDPO can generate far more diverse responses than the baseline methods that are
still relatively aligned with human values in dialog generation and
summarization tasks.
