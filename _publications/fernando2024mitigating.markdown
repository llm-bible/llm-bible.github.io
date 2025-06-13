---
layout: publication
title: 'Mitigating Forgetting In LLM Supervised Fine-tuning And Preference Learning'
authors: Heshan Fernando, Han Shen, Parikshit Ram, Yi Zhou, Horst Samulowitz, Nathalie Baracaldo, Tianyi Chen
conference: "Arxiv"
year: 2024
bibkey: fernando2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.15483"}
  - {name: "Code", url: "https://github.com/heshandevaka/XRIGHT"}
tags: ['Fine-Tuning', 'Tools', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Post-training of pre-trained LLMs, which typically consists of the supervised
fine-tuning (SFT) stage and the preference learning (RLHF or DPO) stage, is
crucial to effective and safe LLM applications. The widely adopted approach in
post-training popular open-source LLMs is to sequentially perform SFT and
RLHF/DPO. However, sequential training is sub-optimal in terms of SFT and
RLHF/DPO trade-off: the LLM gradually forgets about the first stage's training
when undergoing the second stage's training. We theoretically prove the
sub-optimality of sequential post-training. Furthermore, we propose a practical
joint post-training framework with theoretical convergence guarantees and
empirically outperforms sequential post-training framework, while having
similar computational cost. Our code is available at
https://github.com/heshandevaka/XRIGHT.
