---
layout: publication
title: 'Simpledeepsearcher: Deep Information Seeking Via Web-powered Reasoning Trajectory Synthesis'
authors: Shuang Sun, Huatong Song, Yuhao Wang, Ruiyang Ren, Jinhao Jiang, Junjie Zhang, Fei Bai, Jia Deng, Wayne Xin Zhao, Zheng Liu, Lei Fang, Zhongyuan Wang, Ji-rong Wen
conference: "Arxiv"
year: 2025
bibkey: sun2025deep
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16834"}
  - {name: "Code", url: "https://github.com/RUCAIBox/SimpleDeepSearcher"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Fine-Tuning', 'Has Code', 'Applications']
---
Retrieval-augmented generation (RAG) systems have advanced large language models (LLMs) in complex deep search scenarios requiring multi-step reasoning and iterative information retrieval. However, existing approaches face critical limitations that lack high-quality training trajectories or suffer from the distributional mismatches in simulated environments and prohibitive computational costs for real-world deployment. This paper introduces SimpleDeepSearcher, a lightweight yet effective framework that bridges this gap through strategic data engineering rather than complex training paradigms. Our approach synthesizes high-quality training data by simulating realistic user interactions in live web search environments, coupled with a multi-criteria curation strategy that optimizes the diversity and quality of input and output side. Experiments on five benchmarks across diverse domains demonstrate that SFT on only 871 curated samples yields significant improvements over RL-based baselines. Our work establishes SFT as a viable pathway by systematically addressing the data-scarce bottleneck, offering practical insights for efficient deep search systems. Our code is available at https://github.com/RUCAIBox/SimpleDeepSearcher.
