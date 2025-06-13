---
layout: publication
title: 'PROPER: A Progressive Learning Framework For Personalized Large Language Models With Group-level Adaptation'
authors: Linhai Zhang, Jialong Wu, Deyu Zhou, Yulan He
conference: "Arxiv"
year: 2025
bibkey: zhang2025progressive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01303"}
tags: ['Fine-Tuning', 'Training Techniques', 'Tools', 'Pretraining Methods']
---
Personalized large language models (LLMs) aim to tailor their outputs to user
preferences. Recent advances in parameter-efficient fine-tuning (PEFT) methods
have highlighted the effectiveness of adapting population-level LLMs to
personalized LLMs by fine-tuning user-specific parameters with user history.
However, user data is typically sparse, making it challenging to adapt LLMs to
specific user patterns. To address this challenge, we propose PROgressive
PERsonalization (PROPER), a novel progressive learning framework inspired by
meso-level theory in social science. PROPER bridges population-level and
user-level models by grouping users based on preferences and adapting LLMs in
stages. It combines a Mixture-of-Experts (MoE) structure with Low Ranked
Adaptation (LoRA), using a user-aware router to assign users to appropriate
groups automatically. Additionally, a LoRA-aware router is proposed to
facilitate the integration of individual user LoRAs with group-level LoRAs.
Experimental results show that PROPER significantly outperforms SOTA models
across multiple tasks, demonstrating the effectiveness of our approach.
