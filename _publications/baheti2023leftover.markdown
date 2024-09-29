---
layout: publication
title: Leftover Lunch Advantage45;based Offline Reinforcement Learning For Language Models
authors: Baheti Ashutosh, Lu Ximing, Brahman Faeze, Bras Ronan Le, Sap Maarten, Riedl Mark
conference: "Arxiv"
year: 2023
bibkey: baheti2023leftover
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14718"}
  - {name: "Code", url: "https://github.com/abaheti95/LoL&#45;RL"}
tags: ['Agentic', 'Has Code', 'Reinforcement Learning', 'Training Techniques']
---
Reinforcement Learning with Human Feedback (RLHF) is the most prominent method for Language Model (LM) alignment. However RLHF is an unstable and data45;hungry process that continually requires new high45;quality LM45;generated data for finetuning. We introduce Advantage45;Leftover Lunch RL (A45;LoL) a new class of offline policy gradient algorithms that enable RL training on any pre45;existing data. By assuming the entire LM output sequence as a single action A45;LoL allows incorporating sequence45;level classifiers or human45;designed scoring functions as rewards. Subsequently by using LMs value estimate A45;LoL only trains on positive advantage (leftover) data points making it resilient to noise. Overall A45;LoL is an easy45;to45;implement sample45;efficient and stable LM training recipe. We demonstrate the effectiveness of A45;LoL and its variants with a set of four different language generation tasks. We compare against both online RL (PPO) and recent preference45;based (DPO PRO) and reward45;based (GOLD) offline RL baselines. On the commonly45;used RLHF benchmark Helpful and Harmless Assistant (HHA) LMs trained with A45;LoL methods achieve the highest diversity while also being rated more safe and helpful than the baselines according to humans. Additionally in the remaining three tasks A45;LoL could optimize multiple distinct reward functions even when using noisy or suboptimal training data. We also release our experimental code. https://github.com/abaheti95/LoL&#45;RL
