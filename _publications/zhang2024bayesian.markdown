---
layout: publication
title: 'Memsim: A Bayesian Simulator For Evaluating Memory Of Llm-based Personal Assistants'
authors: Zeyu Zhang, Quanyu Dai, Luyu Chen, Zeren Jiang, Rui Li, Jieming Zhu, Xu Chen, Yi Xie, Zhenhua Dong, Ji-rong Wen
conference: "Arxiv"
year: 2024
bibkey: zhang2024bayesian
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.20163'}
  - {name: "Code", url: 'https://github.com/nuster1128/MemSim'}
tags: ['Agentic', 'Has Code']
---
LLM-based agents have been widely applied as personal assistants, capable of
memorizing information from user messages and responding to personal queries.
However, there still lacks an objective and automatic evaluation on their
memory capability, largely due to the challenges in constructing reliable
questions and answers (QAs) according to user messages. In this paper, we
propose MemSim, a Bayesian simulator designed to automatically construct
reliable QAs from generated user messages, simultaneously keeping their
diversity and scalability. Specifically, we introduce the Bayesian Relation
Network (BRNet) and a causal generation mechanism to mitigate the impact of LLM
hallucinations on factual information, facilitating the automatic creation of
an evaluation dataset. Based on MemSim, we generate a dataset in the daily-life
scenario, named MemDaily, and conduct extensive experiments to assess the
effectiveness of our approach. We also provide a benchmark for evaluating
different memory mechanisms in LLM-based agents with the MemDaily dataset. To
benefit the research community, we have released our project at
https://github.com/nuster1128/MemSim.
