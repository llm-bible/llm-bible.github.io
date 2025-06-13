---
layout: publication
title: 'Othink-r1: Intrinsic Fast/slow Thinking Mode Switching For Over-reasoning Mitigation'
authors: Shengjia Zhang, Junjie Wu, Jiawei Chen, Changwang Zhang, Xingyu Lou, Wangchunshu Zhou, Sheng Zhou, Can Wang, Jun Wang
conference: "Arxiv"
year: 2025
bibkey: zhang2025othink
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.02397'}
  - {name: "Code", url: 'https://github.com/AgenticIR-Lab/OThink-R1'}
tags: ['RAG', 'Has Code', 'Agentic']
---
Recent advanced large reasoning models (LRMs) leverage extended chain-of-thought (CoT) reasoning to solve complex tasks, achieving state-of-the-art performance. Despite their success, we identify a critical issue: a substantial portion of simple tasks solved by LRMs can also be addressed by non-reasoning LLMs using significantly fewer tokens, indicating the complex reasoning may not always be necessary. To address this, we systematically analyze the reasoning trajectories of LRMs and present a method utilizing identified paradigms and LLM-Judge to classify these trajectories as either Redundant Reasoning or Essential Reasoning. And we introduce OThink-R1, a method that prunes redundant reasoning steps while preserving logical validity. OThink-R1 dynamically employs the non-thinking mode (fast-thinking) for straightforward problems while engaging in deliberate thinking (slow-thinking) for complex problems. Experiments across mathematical and question-answering tasks demonstrate that OThink-R1 reduces reasoning redundancy by almost 23% on average without compromising accuracy, offering practical guidelines for efficient reasoning models. The code is available at https://github.com/AgenticIR-Lab/OThink-R1.
