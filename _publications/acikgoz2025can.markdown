---
layout: publication
title: 'Can A Single Model Master Both Multi-turn Conversations And Tool Use? Coalm: A Unified Conversational Agentic Language Model'
authors: Emre Can Acikgoz, Jeremiah Greer, Akul Datta, Ze Yang, William Zeng, Oussama Elachqar, Emmanouil Koukoumidis, Dilek Hakkani-tür, Gokhan Tur
conference: "Arxiv"
year: 2025
bibkey: acikgoz2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08820"}
tags: ['Agentic', 'GPT', 'Tools', 'Model Architecture', 'Reinforcement Learning']
---
Large Language Models (LLMs) with API-calling capabilities enabled building
effective Language Agents (LA), while also revolutionizing the conventional
task-oriented dialogue (TOD) paradigm. However, current approaches face a
critical dilemma: TOD systems are often trained on a limited set of target
APIs, requiring new data to maintain their quality when interfacing with new
services, while LAs are not trained to maintain user intent over multi-turn
conversations. Because both robust multi-turn management and advanced function
calling are crucial for effective conversational agents, we evaluate these
skills on three popular benchmarks: MultiWOZ 2.4 (TOD), BFCL V3 (LA), and
API-Bank (LA), and our analyses reveal that specialized approaches excel in one
domain but underperform in the other. To bridge this chasm, we introduce CoALM
(Conversational Agentic Language Model), a unified approach that integrates
both conversational and agentic capabilities. We created CoALM-IT, a carefully
constructed multi-task dataset that interleave multi-turn ReAct reasoning with
complex API usage. Using CoALM-IT, we train three models CoALM 8B, CoALM 70B,
and CoALM 405B, which outperform top domain-specific models, including GPT-4o,
across all three benchmarks. This demonstrates the feasibility of a single
model approach for both TOD and LA, setting a new standard for conversational
agents.
