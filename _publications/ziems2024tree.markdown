---
layout: publication
title: 'TOWER: Tree Organized Weighting For Evaluating Complex Instructions'
authors: Noah Ziems, Zhihan Zhang, Meng Jiang
conference: "Arxiv"
year: 2024
bibkey: ziems2024tree
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.06089'}
tags: ['Reinforcement Learning', 'Tools', 'Applications']
---
Evaluating the ability of large language models (LLMs) to follow complex
human-written instructions is essential for their deployment in real-world
applications. While benchmarks like Chatbot Arena use human judges to assess
model performance, they are resource-intensive and time-consuming. Alternative
methods using LLMs as judges, such as AlpacaEval, MT Bench, WildBench, and
InFoBench offer improvements but still do not capture that certain complex
instruction aspects are more important than others to follow.
  To address this gap, we propose a novel evaluation metric, \textsc\{TOWER\},
that incorporates human-judged importance into the assessment of complex
instruction following. We show that human annotators agree with tree-based
representations of these complex instructions nearly as much as they agree with
other human annotators. We release tree-based annotations of the InFoBench
dataset and the corresponding evaluation code to facilitate future research.
