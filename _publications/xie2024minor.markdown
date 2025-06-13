---
layout: publication
title: 'Minor SFT Loss For LLM Fine-tune To Increase Performance And Reduce Model Deviation'
authors: Shiming Xie, Hong Chen, Fred Yu, Zeye Sun, Xiuyu Wu
conference: "Arxiv"
year: 2024
bibkey: xie2024minor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10642"}
tags: ['Applications', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning']
---
Instruct LLM provide a paradigm used in large scale language model to align
LLM to human preference. The paradigm contains supervised fine tuning and
reinforce learning from human feedback. This paradigm is also used in
downstream scenarios to adapt LLM to specific corpora and applications.
Comparing to SFT, there are many efforts focused on RLHF and several algorithms
being proposed, such as PPO, DPO, IPO, KTO, MinorDPO and etc. Meanwhile most
efforts for SFT are focused on how to collect, filter and mix high quality
data. In this article with insight from DPO and MinorDPO, we propose a training
metric for SFT to measure the discrepancy between the optimized model and the
original model, and a loss function MinorSFT that can increase the training
effectiveness, and reduce the discrepancy between the optimized LLM and
original LLM.
