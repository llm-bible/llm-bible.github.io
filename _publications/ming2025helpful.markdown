---
layout: publication
title: 'Helpful Agent Meets Deceptive Judge: Understanding Vulnerabilities In Agentic Workflows'
authors: Yifei Ming, Zixuan Ke, Xuan-phi Nguyen, Jiayu Wang, Shafiq Joty
conference: "Arxiv"
year: 2025
bibkey: ming2025helpful
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03332"}
tags: ['Agentic', 'Tools', 'Ethics and Bias', 'RAG', 'Reinforcement Learning', 'Security']
---
Agentic workflows -- where multiple large language model (LLM) instances interact to solve tasks -- are increasingly built on feedback mechanisms, where one model evaluates and critiques another. Despite the promise of feedback-driven improvement, the stability of agentic workflows rests on the reliability of the judge. However, judges may hallucinate information, exhibit bias, or act adversarially -- introducing critical vulnerabilities into the workflow. In this work, we present a systematic analysis of agentic workflows under deceptive or misleading feedback. We introduce a two-dimensional framework for analyzing judge behavior, along axes of intent (from constructive to malicious) and knowledge (from parametric-only to retrieval-augmented systems). Using this taxonomy, we construct a suite of judge behaviors and develop WAFER-QA, a new benchmark with critiques grounded in retrieved web evidence to evaluate robustness of agentic workflows against factually supported adversarial feedback. We reveal that even strongest agents are vulnerable to persuasive yet flawed critiques -- often switching correct answers after a single round of misleading feedback. Taking a step further, we study how model predictions evolve over multiple rounds of interaction, revealing distinct behavioral patterns between reasoning and non-reasoning models. Our findings highlight fundamental vulnerabilities in feedback-based workflows and offer guidance for building more robust agentic systems.
