---
layout: publication
title: 'Superhf: Supervised Iterative Learning From Human Feedback'
authors: Gabriel Mukobi, Peter Chatain, Su Fong, Robert Windesheim, Gitta Kutyniok, Kush Bhatia, Silas Alberti
conference: "Arxiv"
year: 2023
bibkey: mukobi2023supervised
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.16763"}
tags: ['Fine-Tuning', 'Responsible AI', 'Agentic', 'GPT', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
While large language models demonstrate remarkable capabilities, they often
present challenges in terms of safety, alignment with human values, and
stability during training. Here, we focus on two prevalent methods used to
align these models, Supervised Fine-Tuning (SFT) and Reinforcement Learning
from Human Feedback (RLHF). SFT is simple and robust, powering a host of
open-source models, while RLHF is a more sophisticated method used in top-tier
models like ChatGPT but also suffers from instability and susceptibility to
reward hacking. We propose a novel approach, Supervised Iterative Learning from
Human Feedback (SuperHF), which seeks to leverage the strengths of both
methods. Our hypothesis is two-fold: that the reward model used in RLHF is
critical for efficient data use and model generalization and that the use of
Proximal Policy Optimization (PPO) in RLHF may not be necessary and could
contribute to instability issues. SuperHF replaces PPO with a simple supervised
loss and a Kullback-Leibler (KL) divergence prior. It creates its own training
data by repeatedly sampling a batch of model outputs and filtering them through
the reward model in an online learning regime. We then break down the reward
optimization problem into three components: robustly optimizing the training
rewards themselves, preventing reward hacking-exploitation of the reward model
that degrades model performance-as measured by a novel METEOR similarity
metric, and maintaining good performance on downstream evaluations. Our
experimental results show SuperHF exceeds PPO-based RLHF on the training
objective, easily and favorably trades off high reward with low reward hacking,
improves downstream calibration, and performs the same on our GPT-4 based
qualitative evaluation scheme all the while being significantly simpler to
implement, highlighting SuperHF's potential as a competitive language model
alignment technique.
