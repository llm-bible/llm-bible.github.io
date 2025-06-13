---
layout: publication
title: 'Reducing Tool Hallucination Via Reliability Alignment'
authors: Hongshen Xu, Zichen Zhu, Lei Pan, Zihan Wang, Su Zhu, Da Ma, Ruisheng Cao, Lu Chen, Kai Yu
conference: "Arxiv"
year: 2024
bibkey: xu2024reducing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.04141'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization', 'Applications', 'Tools']
---
Large Language Models (LLMs) have expanded their capabilities beyond language generation to interact with external tools, enabling automation and real-world applications. However, tool hallucinations, where models either select inappropriate tools or misuse them, pose significant challenges, leading to erroneous task execution, increased computational costs, and reduced system reliability. To systematically address this issue, we define and categorize tool hallucinations into two main types, tool selection hallucination and tool usage hallucination. To evaluate and mitigate these issues, we introduce RelyToolBench, which integrates specialized test cases and novel metrics to assess hallucination-aware task success and efficiency. Finally, we propose Relign, a reliability alignment framework that expands the tool-use action space to include indecisive actions, allowing LLMs to defer tool use, seek clarification, or adjust tool selection dynamically. Through extensive experiments, we demonstrate that Relign significantly reduces tool hallucinations, improves task reliability, and enhances the efficiency of LLM tool interactions.
