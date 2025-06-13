---
layout: publication
title: 'Dancing With Critiques: Enhancing LLM Reasoning With Stepwise Natural Language Self-critique'
authors: Yansi Li, Jiahao Xu, Tian Liang, Xingyu Chen, Zhiwei He, Qiuzhi Liu, Rui Wang, Zhuosheng Zhang, Zhaopeng Tu, Haitao Mi, Dong Yu
conference: "Arxiv"
year: 2025
bibkey: li2025dancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.17363'}
  - {name: "Code", url: 'https://github.com/puddingyeah/PANEL'}
tags: ['Reinforcement Learning', 'RAG', 'Has Code', 'Training Techniques']
---
Enhancing the reasoning capabilities of large language models (LLMs),
particularly for complex tasks requiring multi-step logical deductions, remains
a significant challenge. Traditional inference time scaling methods utilize
scalar reward signals from process reward models to evaluate candidate
reasoning steps, but these scalar rewards lack the nuanced qualitative
information essential for understanding and justifying each step. In this
paper, we propose a novel inference-time scaling approach -- stepwise natural
language self-critique (PANEL), which employs self-generated natural language
critiques as feedback to guide the step-level search process. By generating
rich, human-readable critiques for each candidate reasoning step, PANEL retains
essential qualitative information, facilitating better-informed decision-making
during inference. This approach bypasses the need for task-specific verifiers
and the associated training overhead, making it broadly applicable across
diverse tasks. Experimental results on challenging reasoning benchmarks,
including AIME and GPQA, demonstrate that PANEL significantly enhances
reasoning performance, outperforming traditional scalar reward-based methods.
Our code is available at https://github.com/puddingyeah/PANEL to support and
encourage future research in this promising field.
