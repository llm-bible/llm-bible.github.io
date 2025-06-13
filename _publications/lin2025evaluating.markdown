---
layout: publication
title: 'Robunfr: Evaluating The Robustness Of Large Language Models On Non-functional Requirements Aware Code Generation'
authors: Feng Peter Lin, Dong Jae Peter Kim, Zhenhao Peter Li, Jinqiu Peter Yang, Peter Tse-hsun, Chen
conference: "Arxiv"
year: 2025
bibkey: lin2025evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.22851'}
tags: ['Prompting', 'Security', 'Applications']
---
When using LLMs to address Non-Functional Requirements (NFRs), developers may
behave differently (e.g., expressing the same NFR in different words). Robust
LLMs should output consistent results across these variations; however, this
aspect remains underexplored. We propose RobuNFR for evaluating the robustness
of LLMs in NFR-aware code generation across four NFR dimensions: design,
readability, reliability, and performance, using three methodologies: prompt
variation, regression testing, and diverse workflows. Our experiments show that
RobuNFR reveals robustness issues in the tested LLMs when considering NFRs in
code generation. Specifically, under prompt variation, including NFRs leads to
a decrease in Pass@1 by up to 39 percent and an increase in the standard
deviation from 0.48 to 2.48 compared to the baseline without NFRs (i.e.,
Function-Only). While incorporating NFRs generally improves overall NFR
metrics, it also results in higher prompt sensitivity. In regression settings,
some LLMs exhibit differences across versions, with improvements in one aspect
(e.g., reduced code smells) often accompanied by regressions in another (e.g.,
decreased correctness), revealing inconsistencies that challenge their
robustness. When varying workflows, the tested LLMs show significantly
different NFR-aware code generation capabilities between two workflows: (1)
integrating NFRs and functional requirements into the initial prompt and (2)
enhancing Function-Only-generated code with the same NFR.
