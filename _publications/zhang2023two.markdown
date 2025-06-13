---
layout: publication
title: 'A Two-stage Adaptation Of Large Language Models For Text Ranking'
authors: Longhui Zhang, Yanzhao Zhang, Dingkun Long, Pengjun Xie, Meishan Zhang, Min Zhang
conference: "Arxiv"
year: 2023
bibkey: zhang2023two
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.16720"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training', 'Applications']
---
Text ranking is a critical task in information retrieval. Recent advances in
pre-trained language models (PLMs), especially large language models (LLMs),
present new opportunities for applying them to text ranking. While supervised
fine-tuning (SFT) with ranking data has been widely explored to better align
PLMs with text ranking goals, previous studies have focused primarily on
encoder-only and encoder-decoder PLMs. Research on leveraging decoder-only LLMs
for text ranking remains scarce. An exception to this is RankLLaMA, which uses
direct SFT to explore LLaMA's potential for text ranking. In this work, we
propose a two-stage progressive paradigm to better adapt LLMs to text ranking.
First, we conduct continual pre-training (CPT) of LLMs on a large
weakly-supervised corpus. Second, we perform SFT, and propose an improved
optimization strategy building upon RankLLaMA. Our experimental results on
multiple benchmarks show that our approach outperforms previous methods in both
in-domain and out-domain scenarios.
