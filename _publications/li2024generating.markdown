---
layout: publication
title: 'Generating Equivalent Representations Of Code By A Self-reflection Approach'
authors: Jia Li, Ge Li, Lecheng Wang, Hao Zhu, Zhi Jin
conference: "Arxiv"
year: 2024
bibkey: li2024generating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.03351'}
tags: ['Reinforcement Learning', 'Applications', 'Tools']
---
Equivalent Representations (ERs) of code are textual representations that
preserve the same semantics as the code itself, e.g., natural language comments
and pseudocode. ERs play a critical role in software development and
maintenance. However, how to automatically generate ERs of code remains an open
challenge. In this paper, we propose a self-reflection approach to generating
ERs of code. It enables two Large Language Models (LLMs) to work mutually and
produce an ER through a reflection process. Depending on whether constraints on
ERs are applied, our approach generates ERs in both open and constrained
settings. We conduct a empirical study to generate ERs in two settings and
obtain eight findings. (1) Generating ERs in the open setting. In the open
setting, we allow LLMs to represent code without any constraints, analyzing the
resulting ERs and uncovering five key findings. These findings shed light on
how LLMs comprehend syntactic structures, APIs, and numerical computations in
code. (2) Generating ERs in the constrained setting. In the constrained
setting, we impose constraints on ERs, such as natural language comments,
pseudocode, and flowcharts. This allows our approach to address a range of
software engineering tasks. Based on our experiments, we have three findings
demonstrating that our approach can effectively generate ERs that adhere to
specific constraints, thus supporting various software engineering tasks. (3)
Future directions. We also discuss potential future research directions, such
as deriving intermediate languages for code generation, exploring LLM-friendly
requirement descriptions, and further supporting software engineering tasks. We
believe that this paper will spark discussions in research communities and
inspire many follow-up studies.
