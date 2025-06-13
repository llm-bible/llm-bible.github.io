---
layout: publication
title: 'Dialoguereason: Rule-based RL Sparks Dialogue Reasoning In Llms'
authors: Yubo Shu, Zhewei Huang, Xin Wu, Chen Hu, Shuchang Zhou, Daxin Jiang
conference: "Arxiv"
year: 2025
bibkey: shu2025rule
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.07049'}
tags: ['Attention Mechanism', 'Agentic', 'Interpretability and Explainability', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
We propose DialogueReason, a reasoning paradigm that uncovers the lost roles in monologue-style reasoning models, aiming to boost diversity and coherency of the reasoning process. Recent advances in RL-based large reasoning models have led to impressive long CoT capabilities and high performance on math and science benchmarks. However, these reasoning models rely mainly on monologue-style reasoning, which often limits reasoning diversity and coherency, frequently recycling fixed strategies or exhibiting unnecessary shifts in attention. Our work consists of an analysis of monologue reasoning patterns and the development of a dialogue-based reasoning approach. We first introduce the Compound-QA task, which concatenates multiple problems into a single prompt to assess both diversity and coherency of reasoning. Our analysis shows that Compound-QA exposes weaknesses in monologue reasoning, evidenced by both quantitative metrics and qualitative reasoning traces. Building on the analysis, we propose a dialogue-based reasoning, named DialogueReason, structured around agents, environment, and interactions. Using PPO with rule-based rewards, we train open-source LLMs (Qwen-QWQ and Qwen-Base) to adopt dialogue reasoning. We evaluate trained models on MATH, AIME, and GPQA datasets, showing that the dialogue reasoning model outperforms monologue models under more complex compound questions. Additionally, we discuss how dialogue-based reasoning helps enhance interpretability, facilitate more intuitive human interaction, and inspire advances in multi-agent system design.
