---
layout: publication
title: 'A Critical Look At Tokenwise Reward-guided Text Generation'
authors: Rashid Ahmad, Wu Ruotian, Grosse Julia, Kristiadi Agustinus, Poupart Pascal
conference: "Arxiv"
year: 2024
bibkey: rashid2024critical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07780"}
tags: ['Agentic', 'Applications', 'Fine Tuning', 'GPT', 'Language Modeling', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) can significantly be improved by aligning to
human preferences -- the so-called reinforcement learning from human feedback
(RLHF). However, the cost of fine-tuning an LLM is prohibitive for many users.
Due to their ability to bypass LLM finetuning, tokenwise reward-guided text
generation (RGTG) methods have recently been proposed. They use a reward model
trained on full sequences to score partial sequences during a tokenwise
decoding, in a bid to steer the generation towards sequences with high rewards.
However, these methods have so far been only heuristically motivated and poorly
analyzed. In this work, we show that reward models trained on full sequences
are not compatible with scoring partial sequences. To alleviate this issue, we
propose to explicitly train a Bradley-Terry reward model on partial sequences,
and autoregressively sample from the implied tokenwise policy during decoding
time. We study the property of this reward model and the implied policy. In
particular, we show that this policy is proportional to the ratio of two
distinct RLHF policies. We show that our simple approach outperforms previous
RGTG methods and achieves similar performance as strong offline baselines but
without large-scale LLM finetuning.
