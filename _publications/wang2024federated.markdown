---
layout: publication
title: Flora Federated Fine45;tuning Large Language Models With Heterogeneous Low45;rank Adaptations
authors: Wang Ziyao, Shen Zheyu, He Yexiao, Sun Guoheng, Wang Hongyi, Lyu Lingjuan, Li Ang
conference: "Arxiv"
year: 2024
bibkey: wang2024federated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.05976"}
  - {name: "Code", url: "https://github.com/ATP&#45;1010/FederatedLLM"}
tags: ['Fine Tuning', 'Has Code', 'Multimodal Models', 'Reinforcement Learning', 'Tools']
---
The rapid development of Large Language Models (LLMs) has been pivotal in advancing AI with pre45;trained LLMs being adaptable to diverse downstream tasks through fine45;tuning. Federated learning (FL) further enhances fine45;tuning in a privacy45;aware manner by utilizing clients local data through in45;situ computation eliminating the need for data movement. However fine45;tuning LLMs given their massive scale of parameters poses challenges for clients with constrained and heterogeneous resources in FL. Previous methods employed low45;rank adaptation (LoRA) for efficient federated fine45;tuning but utilized traditional FL aggregation strategies on LoRA adapters. These approaches led to mathematically inaccurate aggregation noise reducing fine45;tuning effectiveness and failing to address heterogeneous LoRAs. In this work we first highlight the mathematical incorrectness of LoRA aggregation in existing federated fine45;tuning methods. We introduce a new approach called FLORA that enables federated fine45;tuning on heterogeneous LoRA adapters across clients through a novel stacking45;based aggregation method. Our approach is noise45;free and seamlessly supports heterogeneous LoRA adapters. Extensive experiments demonstrate FLORA s superior performance in both homogeneous and heterogeneous settings surpassing state45;of45;the45;art methods. We envision this work as a milestone for efficient privacy45;preserving and accurate federated fine45;tuning of LLMs. Our code is available at https://github.com/ATP&#45;1010/FederatedLLM.
