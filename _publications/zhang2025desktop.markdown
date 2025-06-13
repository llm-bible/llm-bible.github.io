---
layout: publication
title: 'UFO2: The Desktop Agentos'
authors: Chaoyun Zhang, He Huang, Chiming Ni, Jian Mu, Si Qin, Shilin He, Lu Wang, Fangkai Yang, Pu Zhao, Chao Du, Liqun Li, Yu Kang, Zhao Jiang, Suzhen Zheng, Rujia Wang, Jiaxu Qian, Minghua Ma, Jian-guang Lou, Qingwei Lin, Saravan Rajmohan, Dongmei Zhang
conference: "Arxiv"
year: 2025
bibkey: zhang2025desktop
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14603"}
tags: ['Agentic', 'Security', 'Model Architecture', 'Efficiency and Optimization', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'RAG', 'Applications']
---
Recent Computer-Using Agents (CUAs), powered by multimodal large language
models (LLMs), offer a promising direction for automating complex desktop
workflows through natural language. However, most existing CUAs remain
conceptual prototypes, hindered by shallow OS integration, fragile
screenshot-based interaction, and disruptive execution.
  We present UFO2, a multiagent AgentOS for Windows desktops that elevates CUAs
into practical, system-level automation. UFO2 features a centralized HostAgent
for task decomposition and coordination, alongside a collection of
application-specialized AppAgent equipped with native APIs, domain-specific
knowledge, and a unified GUI--API action layer. This architecture enables
robust task execution while preserving modularity and extensibility. A hybrid
control detection pipeline fuses Windows UI Automation (UIA) with vision-based
parsing to support diverse interface styles. Runtime efficiency is further
enhanced through speculative multi-action planning, reducing per-step LLM
overhead. Finally, a Picture-in-Picture (PiP) interface enables automation
within an isolated virtual desktop, allowing agents and users to operate
concurrently without interference.
  We evaluate UFO2 across over 20 real-world Windows applications,
demonstrating substantial improvements in robustness and execution accuracy
over prior CUAs. Our results show that deep OS integration unlocks a scalable
path toward reliable, user-aligned desktop automation.
