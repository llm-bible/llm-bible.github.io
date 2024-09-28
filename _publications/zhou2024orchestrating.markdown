---
layout: publication
title: Orchestrating LLMs with Different Personalizations
authors: Zhou Jin Peng, Luo Katie Z, Gu Jingwen, Yuan Jason, Weinberger Kilian Q., Sun Wen
conference: "Arxiv"
year: 2024
bibkey: zhou2024orchestrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.04181"}
tags: ['ARXIV', 'Agentic', 'Fine Tuning', 'LLM', 'Merging', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
This paper presents a novel approach to aligning large language models (LLMs) with individual human preferences sometimes referred to as Reinforcement Learning from Human Feedback (RLPHF). Given stated preferences along multiple dimensions such as helpfulness conciseness or humor the goal is to create an LLM without re-training that best adheres to this specification. Starting from specialized expert LLMs each trained for one such particular preference dimension we propose a black-box method that merges their outputs on a per-token level. We train a lightweight Preference Control Model (PCM) that dynamically translates the preference description and current context into next-token prediction weights. By combining the expert models outputs at the token level our approach dynamically generates text that optimizes the given preference. Empirical tests show that our method matches or surpasses existing preference merging techniques providing a scalable efficient alternative to fine-tuning LLMs for individual personalization.
