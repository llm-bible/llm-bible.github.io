---
layout: publication
title: 'Windows Agent Arena: Evaluating Multi-modal OS Agents At Scale'
authors: Rogerio Bonatti, Dan Zhao, Francesco Bonacci, Dillon Dupont, Sara Abdali, Yinheng Li, Yadong Lu, Justin Wagle, Kazuhito Koishida, Arthur Bucker, Lawrence Jang, Zack Hui
conference: "Arxiv"
year: 2024
bibkey: bonatti2024windows
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.08264"}
  - {name: "Code", url: "https://microsoft.github.io/WindowsAgentArena"}
  - {name: "Code", url: "https://github.com/microsoft/WindowsAgentArena"}
tags: ['Agentic', 'Tools', 'Reinforcement Learning', 'Has Code', 'Applications']
---
Large language models (LLMs) show remarkable potential to act as computer
agents, enhancing human productivity and software accessibility in multi-modal
tasks that require planning and reasoning. However, measuring agent performance
in realistic environments remains a challenge since: (i) most benchmarks are
limited to specific modalities or domains (e.g. text-only, web navigation, Q&A,
coding) and (ii) full benchmark evaluations are slow (on order of magnitude of
days) given the multi-step sequential nature of tasks. To address these
challenges, we introduce the Windows Agent Arena: a reproducible, general
environment focusing exclusively on the Windows operating system (OS) where
agents can operate freely within a real Windows OS and use the same wide range
of applications, tools, and web browsers available to human users when solving
tasks. We adapt the OSWorld framework (Xie et al., 2024) to create 150+ diverse
Windows tasks across representative domains that require agent abilities in
planning, screen understanding, and tool usage. Our benchmark is scalable and
can be seamlessly parallelized in Azure for a full benchmark evaluation in as
little as 20 minutes. To demonstrate Windows Agent Arena's capabilities, we
also introduce a new multi-modal agent, Navi. Our agent achieves a success rate
of 19.5% in the Windows domain, compared to 74.5% performance of an unassisted
human. Navi also demonstrates strong performance on another popular web-based
benchmark, Mind2Web. We offer extensive quantitative and qualitative analysis
of Navi's performance, and provide insights into the opportunities for future
research in agent development and data generation using Windows Agent Arena.
  Webpage: https://microsoft.github.io/WindowsAgentArena
  Code: https://github.com/microsoft/WindowsAgentArena
