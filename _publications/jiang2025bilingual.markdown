---
layout: publication
title: 'Bi''an: A Bilingual Benchmark And Model For Hallucination Detection In Retrieval-augmented Generation'
authors: Zhouyu Jiang, Mengshu Sun, Zhiqiang Zhang, Lei Liang
conference: "Arxiv"
year: 2025
bibkey: jiang2025bilingual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.19209'}
  - {name: "Code", url: 'https://github.com/OpenSPG/KAG'}
tags: ['Reinforcement Learning', 'RAG', 'Has Code', 'Tools']
---
Retrieval-Augmented Generation (RAG) effectively reduces hallucinations in
Large Language Models (LLMs) but can still produce inconsistent or unsupported
content. Although LLM-as-a-Judge is widely used for RAG hallucination detection
due to its implementation simplicity, it faces two main challenges: the absence
of comprehensive evaluation benchmarks and the lack of domain-optimized judge
models. To bridge these gaps, we introduce \textbf\{Bi'an\}, a novel framework
featuring a bilingual benchmark dataset and lightweight judge models. The
dataset supports rigorous evaluation across multiple RAG scenarios, while the
judge models are fine-tuned from compact open-source LLMs. Extensive
experimental evaluations on Bi'anBench show our 14B model outperforms baseline
models with over five times larger parameter scales and rivals state-of-the-art
closed-source LLMs. We will release our data and models soon at
https://github.com/OpenSPG/KAG.
