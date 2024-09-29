---
layout: publication
title: A Two45;stage Adaptation Of Large Language Models For Text Ranking
authors: Zhang Longhui, Zhang Yanzhao, Long Dingkun, Xie Pengjun, Zhang Meishan, Zhang Min
conference: "Arxiv"
year: 2023
bibkey: zhang2023two
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.16720"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Text ranking is a critical task in information retrieval. Recent advances in pre45;trained language models (PLMs) especially large language models (LLMs) present new opportunities for applying them to text ranking. While supervised fine45;tuning (SFT) with ranking data has been widely explored to better align PLMs with text ranking goals previous studies have focused primarily on encoder45;only and encoder45;decoder PLMs. Research on leveraging decoder45;only LLMs for text ranking remains scarce. An exception to this is RankLLaMA which uses direct SFT to explore LLaMAs potential for text ranking. In this work we propose a two45;stage progressive paradigm to better adapt LLMs to text ranking. First we conduct continual pre45;training (CPT) of LLMs on a large weakly45;supervised corpus. Second we perform SFT and propose an improved optimization strategy building upon RankLLaMA. Our experimental results on multiple benchmarks show that our approach outperforms previous methods in both in45;domain and out45;domain scenarios.
