---
layout: publication
title: 'Single-agent Or Multi-agent Systems? Why Not Both?'
authors: Mingyan Gao, Yanzi Li, Banruo Liu, Yifan Yu, Phillip Wang, Ching-yu Lin, Fan Lai
conference: "Arxiv"
year: 2025
bibkey: gao2025single
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.18286'}
tags: ['Agentic', 'Agent', 'Efficiency and Optimization', 'Applications', 'Tools']
---
Multi-agent systems (MAS) decompose complex tasks and delegate subtasks to different large language model (LLM) agents and tools. Prior studies have reported the superior accuracy performance of MAS across diverse domains, enabled by long-horizon context tracking and error correction through role-specific agents. However, the design and deployment of MAS incur higher complexity and runtime cost compared to single-agent systems (SAS). Meanwhile, frontier LLMs, such as OpenAI-o3 and Gemini-2.5-Pro, have rapidly advanced in long-context reasoning, memory retention, and tool usage, mitigating many limitations that originally motivated MAS designs. In this paper, we conduct an extensive empirical study comparing MAS and SAS across various popular agentic applications. We find that the benefits of MAS over SAS diminish as LLM capabilities improve, and we propose efficient mechanisms to pinpoint the error-prone agent in MAS. Furthermore, the performance discrepancy between MAS and SAS motivates our design of a hybrid agentic paradigm, request cascading between MAS and SAS, to improve both efficiency and capability. Our design improves accuracy by 1.1-12% while reducing deployment costs by up to 20% across various agentic applications.
