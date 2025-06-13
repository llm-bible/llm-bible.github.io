---
layout: publication
title: 'Assistive Large Language Model Agents For Socially-aware Negotiation Dialogues'
authors: Yuncheng Hua, Lizhen Qu, Gholamreza Haffari
conference: "Findings of the Association for Computational Linguistics EMNLP 2024"
year: 2024
bibkey: hua2024assistive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01737"}
  - {name: "Code", url: "https://github.com/tk1363704/SADAS"}
tags: ['Agentic', 'Reinforcement Learning', 'Has Code', 'Prompting', 'In-Context Learning']
---
We develop assistive agents based on Large Language Models (LLMs) that aid
interlocutors in business negotiations. Specifically, we simulate business
negotiations by letting two LLM-based agents engage in role play. A third LLM
acts as a remediator agent to rewrite utterances violating norms for improving
negotiation outcomes. We introduce a simple tuning-free and label-free
In-Context Learning (ICL) method to identify high-quality ICL exemplars for the
remediator, where we propose a novel select criteria, called value impact, to
measure the quality of the negotiation outcomes. We provide rich empirical
evidence to demonstrate its effectiveness in negotiations across three
different negotiation topics. We have released our source code and the
generated dataset at: https://github.com/tk1363704/SADAS.
