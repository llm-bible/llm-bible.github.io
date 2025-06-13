---
layout: publication
title: 'A Critical Look At Tokenwise Reward-guided Text Generation'
authors: Ahmad Rashid, Ruotian Wu, Julia Grosse, Agustinus Kristiadi, Pascal Poupart
conference: "Arxiv"
year: 2024
bibkey: rashid2024critical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07780"}
tags: ['Fine-Tuning', 'Agentic', 'GPT', 'Applications', 'Language Modeling', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) can be improved by aligning with human
preferences through fine-tuning -- the so-called reinforcement learning from
human feedback (RLHF). However, the cost of fine-tuning an LLM is prohibitive
for many users. Due to their ability to bypass LLM fine-tuning, prediction-time
tokenwise reward-guided text generation (RGTG) methods have recently been
proposed. They use a reward model trained on full sequences to score partial
sequences during decoding in a bid to steer the generation towards sequences
with high rewards. However, these methods have so far been only heuristically
motivated and poorly analyzed. In this work, we show that reward models trained
on full sequences are not compatible with scoring partial sequences. To
alleviate this issue, we propose to train a Bradley-Terry reward model on
partial sequences explicitly, and autoregressively sample from the implied
tokenwise policy during decoding time. We study the properties of this reward
model and the resulting policy: we show that this policy is proportional to the
ratio of two distinct RLHF policies. Our simple approach outperforms previous
RGTG methods and performs similarly to strong offline baselines without
large-scale LLM finetuning.
