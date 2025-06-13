---
layout: publication
title: 'Amplified Vulnerabilities: Structured Jailbreak Attacks On Llm-based Multi-agent Debate'
authors: Senmao Qi, Yifei Zou, Peng Li, Ziyi Lin, Xiuzhen Cheng, Dongxiao Yu
conference: "Arxiv"
year: 2025
bibkey: qi2025amplified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.16489"}
tags: ['Agentic', 'Security', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Prompting']
---
Multi-Agent Debate (MAD), leveraging collaborative interactions among Large
Language Models (LLMs), aim to enhance reasoning capabilities in complex tasks.
However, the security implications of their iterative dialogues and
role-playing characteristics, particularly susceptibility to jailbreak attacks
eliciting harmful content, remain critically underexplored. This paper
systematically investigates the jailbreak vulnerabilities of four prominent MAD
frameworks built upon leading commercial LLMs (GPT-4o, GPT-4, GPT-3.5-turbo,
and DeepSeek) without compromising internal agents. We introduce a novel
structured prompt-rewriting framework specifically designed to exploit MAD
dynamics via narrative encapsulation, role-driven escalation, iterative
refinement, and rhetorical obfuscation. Our extensive experiments demonstrate
that MAD systems are inherently more vulnerable than single-agent setups.
Crucially, our proposed attack methodology significantly amplifies this
fragility, increasing average harmfulness from 28.14% to 80.34% and achieving
attack success rates as high as 80% in certain scenarios. These findings reveal
intrinsic vulnerabilities in MAD architectures and underscore the urgent need
for robust, specialized defenses prior to real-world deployment.
