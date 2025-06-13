---
layout: publication
title: 'Learning To Use Tools Via Cooperative And Interactive Agents'
authors: Zhengliang Shi, Shen Gao, Xiuyi Chen, Yue Feng, Lingyong Yan, Haibo Shi, Dawei Yin, Pengjie Ren, Suzan Verberne, Zhaochun Ren
conference: "Arxiv"
year: 2024
bibkey: shi2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03031"}
tags: ['Agentic', 'Efficiency and Optimization', 'Distillation', 'Tools']
---
Tool learning empowers large language models (LLMs) as agents to use external
tools and extend their utility. Existing methods employ one single LLM-based
agent to iteratively select and execute tools, thereafter incorporating
execution results into the next action prediction. Despite their progress,
these methods suffer from performance degradation when addressing practical
tasks due to: (1) the pre-defined pipeline with restricted flexibility to
calibrate incorrect actions, and (2) the struggle to adapt a general LLM-based
agent to perform a variety of specialized actions. To mitigate these problems,
we propose ConAgents, a Cooperative and interactive Agents framework, which
coordinates three specialized agents for tool selection, tool execution, and
action calibration separately. ConAgents introduces two communication protocols
to enable the flexible cooperation of agents. To effectively generalize the
ConAgents into open-source models, we also propose specialized action
distillation, enhancing their ability to perform specialized actions in our
framework. Our extensive experiments on three datasets show that the LLMs, when
equipped with the ConAgents, outperform baselines with substantial improvement
(i.e., up to 14% higher success rate).
