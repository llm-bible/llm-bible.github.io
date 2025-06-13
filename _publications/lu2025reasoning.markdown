---
layout: publication
title: 'Reasoning Llms Are Wandering Solution Explorers'
authors: Jiahao Lu, Ziwei Xu, Mohan Kankanhalli
conference: "Arxiv"
year: 2025
bibkey: lu2025reasoning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20296'}
tags: ['Reinforcement Learning', 'Fine-Tuning', 'Prompting', 'Tools']
---
Large Language Models (LLMs) have demonstrated impressive reasoning abilities through test-time computation (TTC) techniques such as chain-of-thought prompting and tree-based reasoning. However, we argue that current reasoning LLMs (RLLMs) lack the ability to systematically explore the solution space. This paper formalizes what constitutes systematic problem solving and identifies common failure modes that reveal reasoning LLMs to be wanderers rather than systematic explorers. Through qualitative and quantitative analysis across multiple state-of-the-art LLMs, we uncover persistent issues: invalid reasoning steps, redundant explorations, hallucinated or unfaithful conclusions, and so on. Our findings suggest that current models' performance can appear to be competent on simple tasks yet degrade sharply as complexity increases. Based on the findings, we advocate for new metrics and tools that evaluate not just final outputs but the structure of the reasoning process itself.
