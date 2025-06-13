---
layout: publication
title: 'Ali-agent: Assessing Llms'' Alignment With Human Values Via Agent-based Evaluation'
authors: Jingnan Zheng, Han Wang, An Zhang, Tai D. Nguyen, Jun Sun, Tat-seng Chua
conference: "2024 Neurips"
year: 2024
bibkey: zheng2024ali
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.14125'}
  - {name: "Code", url: 'https://github.com/SophieZheng998/ALI-Agent.git'}
tags: ['Agentic', 'Has Code', 'RAG', 'Applications', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) can elicit unintended and even harmful content
when misaligned with human values, posing severe risks to users and society. To
mitigate these risks, current evaluation benchmarks predominantly employ
expert-designed contextual scenarios to assess how well LLMs align with human
values. However, the labor-intensive nature of these benchmarks limits their
test scope, hindering their ability to generalize to the extensive variety of
open-world use cases and identify rare but crucial long-tail risks.
Additionally, these static tests fail to adapt to the rapid evolution of LLMs,
making it hard to evaluate timely alignment issues. To address these
challenges, we propose ALI-Agent, an evaluation framework that leverages the
autonomous abilities of LLM-powered agents to conduct in-depth and adaptive
alignment assessments. ALI-Agent operates through two principal stages:
Emulation and Refinement. During the Emulation stage, ALI-Agent automates the
generation of realistic test scenarios. In the Refinement stage, it iteratively
refines the scenarios to probe long-tail risks. Specifically, ALI-Agent
incorporates a memory module to guide test scenario generation, a tool-using
module to reduce human labor in tasks such as evaluating feedback from target
LLMs, and an action module to refine tests. Extensive experiments across three
aspects of human values--stereotypes, morality, and legality--demonstrate that
ALI-Agent, as a general evaluation framework, effectively identifies model
misalignment. Systematic analysis also validates that the generated test
scenarios represent meaningful use cases, as well as integrate enhanced
measures to probe long-tail risks. Our code is available at
https://github.com/SophieZheng998/ALI-Agent.git
