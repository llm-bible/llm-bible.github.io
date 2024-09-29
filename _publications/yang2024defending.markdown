---
layout: publication
title: Guardt2i\: Defending Text-to-image Models From Adversarial Prompts
authors: Yang Yijun, Gao Ruiyuan, Yang Xiao, Zhong Jianyuan, Xu Qiang
conference: "Arxiv"
year: 2024
bibkey: yang2024defending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.01446"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'Responsible AI', 'Security', 'Tools', 'Training Techniques']
---
Recent advancements in Text-to-Image (T2I) models have raised significant safety concerns about their potential misuse for generating inappropriate or Not-Safe-For-Work (NSFW) contents despite existing countermeasures such as NSFW classifiers or model fine-tuning for inappropriate concept removal. Addressing this challenge our study unveils GuardT2I a novel moderation framework that adopts a generative approach to enhance T2I models robustness against adversarial prompts. Instead of making a binary classification GuardT2I utilizes a Large Language Model (LLM) to conditionally transform text guidance embeddings within the T2I models into natural language for effective adversarial prompt detection without compromising the models inherent performance. Our extensive experiments reveal that GuardT2I outperforms leading commercial solutions like OpenAI-Moderation and Microsoft Azure Moderator by a significant margin across diverse adversarial scenarios.
