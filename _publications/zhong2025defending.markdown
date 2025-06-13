---
layout: publication
title: 'RTBAS: Defending LLM Agents Against Prompt Injection And Privacy Leakage'
authors: Peter Yong Zhong, Siyuan Chen, Ruiqi Wang, Mckenna Mccall, Ben L. Titzer, Heather Miller, Phillip B. Gibbons
conference: "Arxiv"
year: 2025
bibkey: zhong2025defending
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.08966'}
tags: ['Attention Mechanism', 'Agentic', 'ACL', 'Security', 'GPT', 'Model Architecture', 'Tools', 'Prompting']
---
Tool-Based Agent Systems (TBAS) allow Language Models (LMs) to use external
tools for tasks beyond their standalone capabilities, such as searching
websites, booking flights, or making financial transactions. However, these
tools greatly increase the risks of prompt injection attacks, where malicious
content hijacks the LM agent to leak confidential data or trigger harmful
actions. Existing defenses (OpenAI GPTs) require user confirmation before every
tool call, placing onerous burdens on users. We introduce Robust TBAS (RTBAS),
which automatically detects and executes tool calls that preserve integrity and
confidentiality, requiring user confirmation only when these safeguards cannot
be ensured. RTBAS adapts Information Flow Control to the unique challenges
presented by TBAS. We present two novel dependency screeners, using
LM-as-a-judge and attention-based saliency, to overcome these challenges.
Experimental results on the AgentDojo Prompt Injection benchmark show RTBAS
prevents all targeted attacks with only a 2% loss of task utility when under
attack, and further tests confirm its ability to obtain near-oracle performance
on detecting both subtle and direct privacy leaks.
