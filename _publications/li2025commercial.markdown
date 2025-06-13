---
layout: publication
title: 'Commercial LLM Agents Are Already Vulnerable To Simple Yet Dangerous Attacks'
authors: Ang Li, Yin Zhou, Vethavikashini Chithrra Raghuram, Tom Goldstein, Micah Goldblum
conference: "Arxiv"
year: 2025
bibkey: li2025commercial
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.08586'}
tags: ['Agentic', 'Security', 'Applications', 'Tools', 'Reinforcement Learning']
---
A high volume of recent ML security literature focuses on attacks against
aligned large language models (LLMs). These attacks may extract private
information or coerce the model into producing harmful outputs. In real-world
deployments, LLMs are often part of a larger agentic pipeline including memory
systems, retrieval, web access, and API calling. Such additional components
introduce vulnerabilities that make these LLM-powered agents much easier to
attack than isolated LLMs, yet relatively little work focuses on the security
of LLM agents. In this paper, we analyze security and privacy vulnerabilities
that are unique to LLM agents. We first provide a taxonomy of attacks
categorized by threat actors, objectives, entry points, attacker observability,
attack strategies, and inherent vulnerabilities of agent pipelines. We then
conduct a series of illustrative attacks on popular open-source and commercial
agents, demonstrating the immediate practical implications of their
vulnerabilities. Notably, our attacks are trivial to implement and require no
understanding of machine learning.
