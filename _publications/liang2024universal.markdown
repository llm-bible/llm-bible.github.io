---
layout: publication
title: 'Universal And Context-independent Triggers For Precise Control Of LLM Outputs'
authors: Jiashuo Liang, Guancheng Li, Yang Yu
conference: "Arxiv"
year: 2024
bibkey: liang2024universal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.14738"}
tags: ['Agentic', 'Security', 'Prompting', 'Applications']
---
Large language models (LLMs) have been widely adopted in applications such as
automated content generation and even critical decision-making systems.
However, the risk of prompt injection allows for potential manipulation of LLM
outputs. While numerous attack methods have been documented, achieving full
control over these outputs remains challenging, often requiring experienced
attackers to make multiple attempts and depending heavily on the prompt
context. Recent advancements in gradient-based white-box attack techniques have
shown promise in tasks like jailbreaks and system prompt leaks. Our research
generalizes gradient-based attacks to find a trigger that is (1) Universal:
effective irrespective of the target output; (2) Context-Independent: robust
across diverse prompt contexts; and (3) Precise Output: capable of manipulating
LLM inputs to yield any specified output with high accuracy. We propose a novel
method to efficiently discover such triggers and assess the effectiveness of
the proposed attack. Furthermore, we discuss the substantial threats posed by
such attacks to LLM-based applications, highlighting the potential for
adversaries to taking over the decisions and actions made by AI agents.
