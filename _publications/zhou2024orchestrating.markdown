---
layout: publication
title: Orchestrating Llms With Different Personalizations
authors: Zhou Jin Peng, Luo Katie Z, Gu Jingwen, Yuan Jason, Weinberger Kilian Q., Sun Wen
conference: "Arxiv"
year: 2024
bibkey: zhou2024orchestrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.04181"}
tags: ['Agentic', 'Merging', 'Reinforcement Learning', 'Training Techniques']
---
This paper presents a novel approach to aligning large language models (LLMs) with individual human preferences sometimes referred to as Reinforcement Learning from textit123;Personalized125; Human Feedback (RLPHF). Given stated preferences along multiple dimensions such as helpfulness conciseness or humor the goal is to create an LLM without re45;training that best adheres to this specification. Starting from specialized expert LLMs each trained for one such particular preference dimension we propose a black45;box method that merges their outputs on a per45;token level. We train a lightweight Preference Control Model (PCM) that dynamically translates the preference description and current context into next45;token prediction weights. By combining the expert models outputs at the token level our approach dynamically generates text that optimizes the given preference. Empirical tests show that our method matches or surpasses existing preference merging techniques providing a scalable efficient alternative to fine45;tuning LLMs for individual personalization.
