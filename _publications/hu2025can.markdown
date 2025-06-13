---
layout: publication
title: 'Can Mllms Generalize To Multi-party Dialog? Exploring Multilingual Response Generation In Complex Scenarios'
authors: Zhongtian Hu, Yiwen Cui, Ronghan Li, Meng Zhao, Lifang Wang
conference: "Arxiv"
year: 2025
bibkey: hu2025can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.11269'}
tags: ['Reinforcement Learning', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Current multilingual large language models(MLLMs) still focus on simple question-answering formats, often overlooking more complex dialogue scenarios. In other words, their capabilities of multilingual large models have yet to be validated in dialogue tasks with intricate structures. We therefore ask, Q1: How well do LLMs generalize to more complex dialog scenarios? Q2: Can supervised fine-tuning on a high-quality parallel benchmark restore this ability? Q3: Does the "multilingual complementarity" effect survive in the setting? To answer these questions, we introduce XMP, a high-quality parallel Multilingual dataset sourced from Multi-party Podcast dialogues, which is the first parallel dataset focusing on multi-party dialogue scenarios. Most samples in the dataset feature three or more participants, discussing a wide range of topics. Through extensive experiments, we find that, R1: MLLMs fail to generalize to multi-party setting, R2 Fine-tuning on XMP improves only marginally, with the 70B model achieving at most a 1% absolute gain over its 8B counterpart; R3: Mixing languages during SFT is usually detrimental, with any benefits being marginal and limited to isolated cases in the 70B model.
