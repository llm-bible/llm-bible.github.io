---
layout: publication
title: 'DANA: Domain-aware Neurosymbolic Agents For Consistency And Accuracy'
authors: Vinh Luong, Sang Dinh, Shruti Raghavan, William Nguyen, Zooey Nguyen, Quynh Le, Hung Vo, Kentaro Maegaito, Loc Nguyen, Thao Nguyen, Anh Hai Ha, Christopher Nguyen
conference: "Arxiv"
year: 2024
bibkey: luong2024domain
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.02823'}
tags: ['Agentic', 'GPT', 'Tools', 'Model Architecture', 'Reinforcement Learning']
---
Large Language Models (LLMs) have shown remarkable capabilities, but their
inherent probabilistic nature often leads to inconsistency and inaccuracy in
complex problem-solving tasks. This paper introduces DANA (Domain-Aware
Neurosymbolic Agent), an architecture that addresses these issues by
integrating domain-specific knowledge with neurosymbolic approaches. We begin
by analyzing current AI architectures, including AutoGPT, LangChain ReAct and
OpenAI's ChatGPT, through a neurosymbolic lens, highlighting how their reliance
on probabilistic inference contributes to inconsistent outputs. In response,
DANA captures and applies domain expertise in both natural-language and
symbolic forms, enabling more deterministic and reliable problem-solving
behaviors. We implement a variant of DANA using Hierarchical Task Plans (HTPs)
in the open-source OpenSSA framework. This implementation achieves over 90%
accuracy on the FinanceBench financial-analysis benchmark, significantly
outperforming current LLM-based systems in both consistency and accuracy.
Application of DANA in physical industries such as semiconductor shows that its
flexible architecture for incorporating knowledge is effective in mitigating
the probabilistic limitations of LLMs and has potential in tackling complex,
real-world problems that require reliability and precision.
