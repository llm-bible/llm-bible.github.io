---
layout: publication
title: 'Codecrash: Stress Testing LLM Reasoning Under Structural And Semantic Perturbations'
authors: Man Ho Lam, Chaozheng Wang, Jen-tse Huang, Michael R. Lyu
conference: "Arxiv"
year: 2025
bibkey: lam2025stress
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14119"}
  - {name: "Code", url: "https://cuhk-arise.github.io/CodeCrash/"}
tags: ['Prompting', 'Security', 'Has Code', 'Reinforcement Learning']
---
Large Language Models (LLMs) have recently demonstrated strong capabilities in code-related tasks, yet their robustness in code comprehension and reasoning remains insufficiently explored. We present CodeCrash, a comprehensive stress-testing benchmark comprising 1,279 questions from two established datasets, CruxEval and LiveCodeBench, designed to evaluate model reasoning reliability under non-standard coding environments. We systematically evaluate 17 LLMs across input and output prediction tasks using direct and Chain-of-Thought prompting approaches, revealing that LLMs are particularly vulnerable to disorganized code and overly reliant on natural language cues: aggregated structural perturbations result in over 14 percentage points (pp) of degradation, while textual perturbations cause a performance drop of over 11 pp. Moreover, self-reflective mechanisms in state-of-the-art reasoning models significantly increase token usage by 2-3 times, reduce output confidence, and even lead to catastrophic reasoning failures when faced with targeted perturbations -- for instance, QwQ-32B generates over 12,000 redundant tokens under reasoning-level perturbations. CodeCrash provides a rigorous benchmark for evaluating robustness in code understanding, guiding future research toward more reliable and resilient LLMs in code reasoning. The benchmark code, perturbed datasets, and full leaderboard are publicly available at https://cuhk-arise.github.io/CodeCrash/ .
