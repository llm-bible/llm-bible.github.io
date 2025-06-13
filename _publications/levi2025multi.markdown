---
layout: publication
title: 'Intellagent: A Multi-agent Framework For Evaluating Conversational AI Systems'
authors: Elad Levi, Ilan Kadar
conference: "Arxiv"
year: 2025
bibkey: levi2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.11067"}
  - {name: "Code", url: "https://github.com/plurai-ai/intellagent"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Applications', 'Reinforcement Learning', 'Has Code']
---
Large Language Models (LLMs) are transforming artificial intelligence,
evolving into task-oriented systems capable of autonomous planning and
execution. One of the primary applications of LLMs is conversational AI
systems, which must navigate multi-turn dialogues, integrate domain-specific
APIs, and adhere to strict policy constraints. However, evaluating these agents
remains a significant challenge, as traditional methods fail to capture the
complexity and variability of real-world interactions. We introduce
IntellAgent, a scalable, open-source multi-agent framework designed to evaluate
conversational AI systems comprehensively. IntellAgent automates the creation
of diverse, synthetic benchmarks by combining policy-driven graph modeling,
realistic event generation, and interactive user-agent simulations. This
innovative approach provides fine-grained diagnostics, addressing the
limitations of static and manually curated benchmarks with coarse-grained
metrics. IntellAgent represents a paradigm shift in evaluating conversational
AI. By simulating realistic, multi-policy scenarios across varying levels of
complexity, IntellAgent captures the nuanced interplay of agent capabilities
and policy constraints. Unlike traditional methods, it employs a graph-based
policy model to represent relationships, likelihoods, and complexities of
policy interactions, enabling highly detailed diagnostics. IntellAgent also
identifies critical performance gaps, offering actionable insights for targeted
optimization. Its modular, open-source design supports seamless integration of
new domains, policies, and APIs, fostering reproducibility and community
collaboration. Our findings demonstrate that IntellAgent serves as an effective
framework for advancing conversational AI by addressing challenges in bridging
research and deployment. The framework is available at
https://github.com/plurai-ai/intellagent
