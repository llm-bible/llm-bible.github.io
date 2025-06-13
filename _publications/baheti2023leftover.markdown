---
layout: publication
title: 'Leftover Lunch: Advantage-based Offline Reinforcement Learning For Language Models'
authors: Ashutosh Baheti, Ximing Lu, Faeze Brahman, Ronan Le Bras, Maarten Sap, Mark Riedl
conference: "Arxiv"
year: 2023
bibkey: baheti2023leftover
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14718"}
  - {name: "Code", url: "https://github.com/abaheti95/LoL-RL"}
tags: ['Agentic', 'Training Techniques', 'Has Code', 'Reinforcement Learning']
---
Reinforcement Learning with Human Feedback (RLHF) is the most prominent
method for Language Model (LM) alignment. However, RLHF is an unstable and
data-hungry process that continually requires new high-quality LM-generated
data for finetuning. We introduce Advantage-Leftover Lunch RL (A-LoL), a new
class of offline policy gradient algorithms that enable RL training on any
pre-existing data. By assuming the entire LM output sequence as a single
action, A-LoL allows incorporating sequence-level classifiers or human-designed
scoring functions as rewards. Subsequently, by using LM's value estimate, A-LoL
only trains on positive advantage (leftover) data points, making it resilient
to noise. Overall, A-LoL is an easy-to-implement, sample-efficient, and stable
LM training recipe.
  We demonstrate the effectiveness of A-LoL and its variants with a set of four
different language generation tasks. We compare against both online RL (PPO)
and recent preference-based (DPO, PRO) and reward-based (GOLD) offline RL
baselines. On the commonly-used RLHF benchmark, Helpful and Harmless Assistant
(HHA), LMs trained with A-LoL methods achieve the highest diversity while also
being rated more safe and helpful than the baselines according to humans.
Additionally, in the remaining three tasks, A-LoL could optimize multiple
distinct reward functions even when using noisy or suboptimal training data.
  We also release our experimental code. https://github.com/abaheti95/LoL-RL
