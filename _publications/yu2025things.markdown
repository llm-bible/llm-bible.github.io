---
layout: publication
title: '\(c^3\)-bench: The Things Real Disturbing LLM Based Agent In Multi-tasking'
authors: Peijie Yu, Yifan Yang, Jinjian Li, Zelong Zhang, Haorui Wang, Xiao Feng, Feng Zhang
conference: "Arxiv"
year: 2025
bibkey: yu2025things
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.18746'}
  - {name: "Code", url: 'https://github.com/yupeijei1997/C3-Bench'}
tags: ['Agentic', 'Has Code', 'Interpretability and Explainability', 'RAG', 'Security', 'Tools', 'Reinforcement Learning']
---
Agents based on large language models leverage tools to modify environments, revolutionizing how AI interacts with the physical world. Unlike traditional NLP tasks that rely solely on historical dialogue for responses, these agents must consider more complex factors, such as inter-tool relationships, environmental feedback and previous decisions, when making choices. Current research typically evaluates agents via multi-turn dialogues. However, it overlooks the influence of these critical factors on agent behavior. To bridge this gap, we present an open-source and high-quality benchmark \\(C^3\\)-Bench. This benchmark integrates attack concepts and applies univariate analysis to pinpoint key elements affecting agent robustness. In concrete, we design three challenges: navigate complex tool relationships, handle critical hidden information and manage dynamic decision paths. Complementing these challenges, we introduce fine-grained metrics, innovative data collection algorithms and reproducible evaluation methods. Extensive experiments are conducted on 49 mainstream agents, encompassing general fast-thinking, slow-thinking and domain-specific models. We observe that agents have significant shortcomings in handling tool dependencies, long context information dependencies and frequent policy-type switching. In essence, \\(C^3\\)-Bench aims to expose model vulnerabilities through these challenges and drive research into the interpretability of agent performance. The benchmark is publicly available at https://github.com/yupeijei1997/C3-Bench.
