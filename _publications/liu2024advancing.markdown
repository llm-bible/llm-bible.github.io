---
layout: publication
title: Advancing Adversarial Suffix Transfer Learning On Aligned Large Language Models
authors: Liu Hongfu, Xie Yuxi, Wang Ye, Shieh Michael
conference: "Arxiv"
year: 2024
bibkey: liu2024advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.14866"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'RAG', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Tools']
---
Language Language Models (LLMs) face safety concerns due to potential misuse by malicious users. Recent red45;teaming efforts have identified adversarial suffixes capable of jailbreaking LLMs using the gradient45;based search algorithm Greedy Coordinate Gradient (GCG). However GCG struggles with computational inefficiency limiting further investigations regarding suffix transferability and scalability across models and data. In this work we bridge the connection between search efficiency and suffix transferability. We propose a two45;stage transfer learning framework DeGCG which decouples the search process into behavior45;agnostic pre45;searching and behavior45;relevant post45;searching. Specifically we employ direct first target token optimization in pre45;searching to facilitate the search process. We apply our approach to cross45;model cross45;data and self45;transfer scenarios. Furthermore we introduce an interleaved variant of our approach i45;DeGCG which iteratively leverages self45;transferability to accelerate the search process. Experiments on HarmBench demonstrate the efficiency of our approach across various models and domains. Notably our i45;DeGCG outperforms the baseline on Llama245;chat45;7b with ASRs of 43.9 (+22.2) and 39.0 (+19.5) on valid and test sets respectively. Further analysis on cross45;model transfer indicates the pivotal role of first target token optimization in leveraging suffix transferability for efficient searching.
