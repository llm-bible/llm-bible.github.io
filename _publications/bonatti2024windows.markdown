---
layout: publication
title: Windows Agent Arena Evaluating Multi45;modal OS Agents At Scale
authors: Bonatti Rogerio, Zhao Dan, Bonacci Francesco, Dupont Dillon, Abdali Sara, Li Yinheng, Wagle Justin, Koishida Kazuhito, Bucker Arthur, Jang Lawrence, Hui Zack
conference: "Arxiv"
year: 2024
bibkey: bonatti2024windows
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.08264"}
  - {name: "Code", url: "https://microsoft.github.io/WindowsAgentArena"}
  - {name: "Code", url: "https://github.com/microsoft/WindowsAgentArena"}
tags: ['Agentic', 'Applications', 'Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Tools']
---
Large language models (LLMs) show remarkable potential to act as computer agents enhancing human productivity and software accessibility in multi45;modal tasks that require planning and reasoning. However measuring agent performance in realistic environments remains a challenge since (i) most benchmarks are limited to specific modalities or domains (e.g. text45;only web navigation Qamp;A coding) and (ii) full benchmark evaluations are slow (on order of magnitude of days) given the multi45;step sequential nature of tasks. To address these challenges we introduce the Windows Agent Arena a reproducible general environment focusing exclusively on the Windows operating system (OS) where agents can operate freely within a real Windows OS and use the same wide range of applications tools and web browsers available to human users when solving tasks. We adapt the OSWorld framework (Xie et al. 2024) to create 150+ diverse Windows tasks across representative domains that require agent abilities in planning screen understanding and tool usage. Our benchmark is scalable and can be seamlessly parallelized in Azure for a full benchmark evaluation in as little as 20 minutes. To demonstrate Windows Agent Arenas capabilities we also introduce a new multi45;modal agent Navi. Our agent achieves a success rate of 19.537; in the Windows domain compared to 74.537; performance of an unassisted human. Navi also demonstrates strong performance on another popular web45;based benchmark Mind2Web. We offer extensive quantitative and qualitative analysis of Navis performance and provide insights into the opportunities for future research in agent development and data generation using Windows Agent Arena. Webpage https://microsoft.github.io/WindowsAgentArena Code https://github.com/microsoft/WindowsAgentArena
