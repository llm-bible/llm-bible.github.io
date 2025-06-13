---
layout: publication
title: 'Metareflection: Learning Instructions For Language Agents Using Past Reflections'
authors: Priyanshu Gupta, Shashank Kirtania, Ananya Singha, Sumit Gulwani, Arjun Radhakrishna, Sherry Shi, Gustavo Soares
conference: "Arxiv"
year: 2024
bibkey: gupta2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13009"}
tags: ['Agentic', 'GPT', 'Efficiency and Optimization', 'Applications', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Prompting']
---
The popularity of Large Language Models (LLMs) have unleashed a new age
ofLanguage Agents for solving a diverse range of tasks. While contemporary
frontier LLMs are capable enough to power reasonably good Language agents, the
closed-API model makes it hard to improve in cases they perform sub-optimally.
To address this, recent works have explored ways to improve their performance
using techniques like self-reflection and prompt optimization. Unfortunately,
techniques like self-reflection can be used only in an online setup, while
contemporary prompt optimization techniques are designed and tested to work on
simple tasks. To this end, we introduce MetaReflection, a novel offline
reinforcement learning technique that enhances the performance of Language
Agents by augmenting a semantic memory based on experiential learnings from
past trials. We demonstrate the efficacy of MetaReflection by evaluating across
multiple domains, including complex logical reasoning, biomedical semantic
similarity, open world question answering, and vulnerability threat detection,
in Infrastructure-as-Code, spanning different agent designs. MetaReflection
boosts Language agents' performance by 4% to 16.82% over the raw GPT-4 baseline
and performs on par with existing state-of-the-art prompt optimization
techniques while requiring fewer LLM calls.
