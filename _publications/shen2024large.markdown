---
layout: publication
title: Shortcutsbench A Large45;scale Real45;world Benchmark For Api45;based Agents
authors: Shen Haiyang, Li Yue, Meng Desong, Cai Dongqi, Qi Sheng, Zhang Li, Xu Mengwei, Ma Yun
conference: "Arxiv"
year: 2024
bibkey: shen2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00132"}
  - {name: "Code", url: "https://github.com/eachsheep/shortcutsbench&#125;"}
tags: ['Agentic', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools']
---
Recent advancements in integrating large language models (LLMs) with application programming interfaces (APIs) have gained significant interest in both academia and industry. These API45;based agents leveraging the strong autonomy and planning capabilities of LLMs can efficiently solve problems requiring multi45;step actions. However their ability to handle multi45;dimensional difficulty levels diverse task types and real45;world demands through APIs remains unknown. In this paper we introduce textsc123;ShortcutsBench125; a large45;scale benchmark for the comprehensive evaluation of API45;based agents in solving tasks with varying levels of difficulty diverse task types and real45;world demands. textsc123;ShortcutsBench125; includes a wealth of real APIs from Apple Inc.s operating systems refined user queries from shortcuts human45;annotated high45;quality action sequences from shortcut developers and accurate parameter filling values about primitive parameter types enum parameter types outputs from previous actions and parameters that need to request necessary information from the system or user. Our extensive evaluation of agents built with 5 leading open45;source (size = 57B) and 4 closed45;source LLMs (e.g. Gemini45;1.545;Pro and GPT45;3.5) reveals significant limitations in handling complex queries related to API selection parameter filling and requesting necessary information from systems and users. These findings highlight the challenges that API45;based agents face in effectively fulfilling real and complex user queries. All datasets code and experimental results will be available at url123;https://github.com/eachsheep/shortcutsbench&#125;.
