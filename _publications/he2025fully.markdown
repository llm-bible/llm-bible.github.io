---
layout: publication
title: 'R1-T1: Fully Incentivizing Translation Capability In Llms Via Reasoning Learning'
authors: Minggui He, Yilun Liu, Shimin Tao, Yuanchang Luo, Hongyong Zeng, Chang Su, Li Zhang, Hongxia Ma, Daimeng Wei, Weibin Meng, Hao Yang, Boxing Chen, Osamu Yoshie
conference: "Arxiv"
year: 2025
bibkey: he2025fully
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19735"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Despite recent breakthroughs in reasoning-enhanced large language models (LLMs) like DeepSeek-R1, incorporating inference-time reasoning into machine translation (MT), where human translators naturally employ structured, multi-layered reasoning chain-of-thoughts (CoTs), is yet underexplored. Existing methods either design a fixed CoT tailored for a specific MT sub-task (e.g., literature translation), or rely on synthesizing CoTs unaligned with humans and supervised fine-tuning (SFT) prone to overfitting, limiting their adaptability to diverse translation scenarios. This paper introduces R1-Translator (R1-T1), a novel framework to achieve inference-time reasoning for general MT via reinforcement learning (RL) with human-aligned CoTs comprising six common patterns. Our approach pioneers three innovations: (1) extending reasoning-based translation to broader MT scenarios (e.g., multilingual MT, domain MT) unseen in the training phase; (2) formalizing six expert-curated CoT templates that mirror hybrid human strategies like context-aware paraphrasing and back translation; and (3) enabling self-evolving CoT discovery through RL. Both human and automatic evaluation results indicate a steady translation performance improvement in a total of 10+ languages and 40+ translation directions on Flores-101 test set and four domain-specific MT tasks, especially on the languages unseen from training.
