---
layout: publication
title: Shortcutsbench A Large-scale Real-world Benchmark For Api-based Agents
authors: Shen Haiyang, Li Yue, Meng Desong, Cai Dongqi, Qi Sheng, Zhang Li, Xu Mengwei, Ma Yun
conference: "Arxiv"
year: 2024
bibkey: shen2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00132"}
  - {name: "Code", url: "https://github.com/eachsheep/shortcutsbench"}
tags: ['Agentic', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools']
---
Recent advancements in integrating large language models (LLMs) with application programming interfaces (APIs) have gained significant interest in both academia and industry. These API-based agents leveraging the strong autonomy and planning capabilities of LLMs can efficiently solve problems requiring multi-step actions. However their ability to handle multi-dimensional difficulty levels diverse task types and real-world demands through APIs remains unknown. In this paper we introduce (textscShortcutsBench) a large-scale benchmark for the comprehensive evaluation of API-based agents in solving tasks with varying levels of difficulty diverse task types and real-world demands. (textscShortcutsBench) includes a wealth of real APIs from Apple Inc.s operating systems refined user queries from shortcuts human-annotated high-quality action sequences from shortcut developers and accurate parameter filling values about primitive parameter types enum parameter types outputs from previous actions and parameters that need to request necessary information from the system or user. Our extensive evaluation of agents built with 5 leading open-source (size = 57B) and 4 closed-source LLMs (e.g. Gemini-1.5-Pro and GPT-3.5) reveals significant limitations in handling complex queries related to API selection parameter filling and requesting necessary information from systems and users. These findings highlight the challenges that API-based agents face in effectively fulfilling real and complex user queries. All datasets code and experimental results will be available at (url)https://github.com/eachsheep/shortcutsbench\}."
