---
layout: publication
title: 'Token-efficient Prompt Injection Attack: Provoking Cessation In LLM Reasoning Via Adaptive Token Compression'
authors: Yu Cui, Yujun Cai, Yiwei Wang
conference: "Arxiv"
year: 2025
bibkey: cui2025token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.20493"}
tags: ['Security', 'Tools', 'Reinforcement Learning', 'Prompting', 'Applications']
---
While reasoning large language models (LLMs) demonstrate remarkable
performance across various tasks, they also contain notable security
vulnerabilities. Recent research has uncovered a "thinking-stopped"
vulnerability in DeepSeek-R1, where model-generated reasoning tokens can
forcibly interrupt the inference process, resulting in empty responses that
compromise LLM-integrated applications. However, existing methods triggering
this vulnerability require complex mathematical word problems with long
prompts--even exceeding 5,000 tokens. To reduce the token cost and formally
define this vulnerability, we propose a novel prompt injection attack named
"Reasoning Interruption Attack", based on adaptive token compression. We
demonstrate that simple standalone arithmetic tasks can effectively trigger
this vulnerability, and the prompts based on such tasks exhibit simpler logical
structures than mathematical word problems. We develop a systematic approach to
efficiently collect attack prompts and an adaptive token compression framework
that utilizes LLMs to automatically compress these prompts. Experiments show
our compression framework significantly reduces prompt length while maintaining
effective attack capabilities. We further investigate the attack's performance
via output prefix and analyze the underlying causes of the vulnerability,
providing valuable insights for improving security in reasoning LLMs.
