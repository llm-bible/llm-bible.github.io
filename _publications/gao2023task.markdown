---
layout: publication
title: 'ASSISTGUI: Task-oriented Desktop Graphical User Interface Automation'
authors: Difei Gao, Lei Ji, Zechen Bai, Mingyu Ouyang, Peiran Li, Dongxing Mao, Qinchen Wu, Weichen Zhang, Peiyi Wang, Xiangwu Guo, Hengxu Wang, Luowei Zhou, Mike Zheng Shou
conference: "Arxiv"
year: 2023
bibkey: gao2023task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.13108"}
tags: ['Agentic', 'Tools', 'Applications', 'RAG', 'Reinforcement Learning']
---
Graphical User Interface (GUI) automation holds significant promise for
assisting users with complex tasks, thereby boosting human productivity.
Existing works leveraging Large Language Model (LLM) or LLM-based AI agents
have shown capabilities in automating tasks on Android and Web platforms.
However, these tasks are primarily aimed at simple device usage and
entertainment operations. This paper presents a novel benchmark, AssistGUI, to
evaluate whether models are capable of manipulating the mouse and keyboard on
the Windows platform in response to user-requested tasks. We carefully
collected a set of 100 tasks from nine widely-used software applications, such
as, After Effects and MS Word, each accompanied by the necessary project files
for better evaluation. Moreover, we propose an advanced Actor-Critic Embodied
Agent framework, which incorporates a sophisticated GUI parser driven by an
LLM-agent and an enhanced reasoning mechanism adept at handling lengthy
procedural tasks. Our experimental results reveal that our GUI Parser and
Reasoning mechanism outshine existing methods in performance. Nevertheless, the
potential remains substantial, with the best model attaining only a 46% success
rate on our benchmark. We conclude with a thorough analysis of the current
methods' limitations, setting the stage for future breakthroughs in this
domain.
