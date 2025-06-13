---
layout: publication
title: 'System Message Generation For User Preferences Using Open-source Models'
authors: Minbyul Jeong, Jungho Cho, Minsoo Khang, Dawoon Jung, Teakgyu Hong
conference: "Arxiv"
year: 2025
bibkey: jeong2025system
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11330"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
System messages play a crucial role in interactions with large language models (LLMs), often serving as prompts to initiate conversations. Through system messages, users can assign specific roles, perform intended tasks, incorporate background information, and specify various output formats and communication styles. Despite such versatility, publicly available datasets often lack system messages and are subject to strict license constraints in industrial applications. Moreover, manually annotating system messages that align with user instructions is resource-intensive. In light of these challenges, we introduce SysGen, a pipeline for generating system messages that better align assistant responses with user instructions using existing supervised fine-tuning datasets that lack system messages. Training open-source models on SysGen data yields substantial improvements in both single-turn (Multifacet) and multi-turn (SysBench) conversation benchmarks. Notably, our method shows strong gains in shorter conversations, suggesting that it enhances early-stage interaction effectiveness. Our qualitative analysis further emphasizes the value of diverse and structured system messages in improving LLM adaptability across varied user scenarios.
