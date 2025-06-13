---
layout: publication
title: 'Logic Jailbreak: Efficiently Unlocking LLM Safety Restrictions Through Formal Logical Expression'
authors: Jingyu Peng, Maolin Wang, Nan Wang, Xiangyu Zhao, Jiatong Li, Kai Zhang, Qi Liu
conference: "Arxiv"
year: 2025
bibkey: peng2025logic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13527"}
tags: ['Responsible AI', 'RAG', 'Reinforcement Learning', 'Security', 'Prompting']
---
Despite substantial advancements in aligning large language models (LLMs) with human values, current safety mechanisms remain susceptible to jailbreak attacks. We hypothesize that this vulnerability stems from distributional discrepancies between alignment-oriented prompts and malicious prompts. To investigate this, we introduce LogiBreak, a novel and universal black-box jailbreak method that leverages logical expression translation to circumvent LLM safety systems. By converting harmful natural language prompts into formal logical expressions, LogiBreak exploits the distributional gap between alignment data and logic-based inputs, preserving the underlying semantic intent and readability while evading safety constraints. We evaluate LogiBreak on a multilingual jailbreak dataset spanning three languages, demonstrating its effectiveness across various evaluation settings and linguistic contexts.
