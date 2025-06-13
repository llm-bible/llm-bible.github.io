---
layout: publication
title: 'Reasoning-augmented Conversation For Multi-turn Jailbreak Attacks On Large Language Models'
authors: Zonghao Ying, Deyue Zhang, Zonglei Jing, Yisong Xiao, Quanchen Zou, Aishan Liu, Siyuan Liang, Xiangzheng Zhang, Xianglong Liu, Dacheng Tao
conference: "Arxiv"
year: 2025
bibkey: ying2025reasoning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.11054'}
  - {name: "Code", url: 'https://github.com/NY1024/RACE'}
tags: ['Has Code', 'RAG', 'Security', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Responsible AI']
---
Multi-turn jailbreak attacks simulate real-world human interactions by
engaging large language models (LLMs) in iterative dialogues, exposing critical
safety vulnerabilities. However, existing methods often struggle to balance
semantic coherence with attack effectiveness, resulting in either benign
semantic drift or ineffective detection evasion. To address this challenge, we
propose Reasoning-Augmented Conversation, a novel multi-turn jailbreak
framework that reformulates harmful queries into benign reasoning tasks and
leverages LLMs' strong reasoning capabilities to compromise safety alignment.
Specifically, we introduce an attack state machine framework to systematically
model problem translation and iterative reasoning, ensuring coherent query
generation across multiple turns. Building on this framework, we design
gain-guided exploration, self-play, and rejection feedback modules to preserve
attack semantics, enhance effectiveness, and sustain reasoning-driven attack
progression. Extensive experiments on multiple LLMs demonstrate that RACE
achieves state-of-the-art attack effectiveness in complex conversational
scenarios, with attack success rates (ASRs) increasing by up to 96%. Notably,
our approach achieves ASRs of 82% and 92% against leading commercial models,
OpenAI o1 and DeepSeek R1, underscoring its potency. We release our code at
https://github.com/NY1024/RACE to facilitate further research in this critical
domain.
