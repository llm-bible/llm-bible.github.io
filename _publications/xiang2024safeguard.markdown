---
layout: publication
title: 'Guardagent: Safeguard LLM Agents By A Guard Agent Via Knowledge-enabled Reasoning'
authors: Zhen Xiang, Linzhi Zheng, Yanjie Li, Junyuan Hong, Qinbin Li, Han Xie, Jiawei Zhang, Zidi Xiong, Chulin Xie, Carl Yang, Dawn Song, Bo Li
conference: "Arxiv"
year: 2024
bibkey: xiang2024safeguard
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.09187"}
  - {name: "Code", url: "https://guardagent.github.io/"}
tags: ['Responsible AI', 'Agentic', 'Security', 'Tools', 'Has Code']
---
The rapid advancement of large language model (LLM) agents has raised new concerns regarding their safety and security. In this paper, we propose GuardAgent, the first guardrail agent to protect target agents by dynamically checking whether their actions satisfy given safety guard requests. Specifically, GuardAgent first analyzes the safety guard requests to generate a task plan, and then maps this plan into guardrail code for execution. By performing the code execution, GuardAgent can deterministically follow the safety guard request and safeguard target agents. In both steps, an LLM is utilized as the reasoning component, supplemented by in-context demonstrations retrieved from a memory module storing experiences from previous tasks. In addition, we propose two novel benchmarks: EICU-AC benchmark to assess the access control for healthcare agents and Mind2Web-SC benchmark to evaluate the safety policies for web agents. We show that GuardAgent effectively moderates the violation actions for different types of agents on these two benchmarks with over 98% and 83% guardrail accuracies, respectively. Project page: https://guardagent.github.io/
