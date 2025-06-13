---
layout: publication
title: 'In Prospect And Retrospect: Reflective Memory Management For Long-term Personalized Dialogue Agents'
authors: Zhen Tan, Jun Yan, I-hung Hsu, Rujun Han, Zifeng Wang, Long T. Le, Yiwen Song, Yanfei Chen, Hamid Palangi, George Lee, Anand Iyer, Tianlong Chen, Huan Liu, Chen-yu Lee, Tomas Pfister
conference: "Arxiv"
year: 2025
bibkey: tan2025prospect
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.08026'}
tags: ['Reinforcement Learning', 'RAG', 'Agentic', 'Applications']
---
Large Language Models (LLMs) have made significant progress in open-ended
dialogue, yet their inability to retain and retrieve relevant information from
long-term interactions limits their effectiveness in applications requiring
sustained personalization. External memory mechanisms have been proposed to
address this limitation, enabling LLMs to maintain conversational continuity.
However, existing approaches struggle with two key challenges. First, rigid
memory granularity fails to capture the natural semantic structure of
conversations, leading to fragmented and incomplete representations. Second,
fixed retrieval mechanisms cannot adapt to diverse dialogue contexts and user
interaction patterns. In this work, we propose Reflective Memory Management
(RMM), a novel mechanism for long-term dialogue agents, integrating forward-
and backward-looking reflections: (1) Prospective Reflection, which dynamically
summarizes interactions across granularities-utterances, turns, and
sessions-into a personalized memory bank for effective future retrieval, and
(2) Retrospective Reflection, which iteratively refines the retrieval in an
online reinforcement learning (RL) manner based on LLMs' cited evidence.
Experiments show that RMM demonstrates consistent improvement across various
metrics and benchmarks. For example, RMM shows more than 10% accuracy
improvement over the baseline without memory management on the LongMemEval
dataset.
