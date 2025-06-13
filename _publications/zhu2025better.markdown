---
layout: publication
title: 'Skyladder: Better And Faster Pretraining Via Context Window Scheduling'
authors: Tongyao Zhu, Qian Liu, Haonan Wang, Shiqi Chen, Xiangming Gu, Tianyu Pang, Min-yen Kan
conference: "Arxiv"
year: 2025
bibkey: zhu2025better
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.15450"}
  - {name: "Code", url: "https://github.com/sail-sg/SkyLadder"}
tags: ['Pretraining Methods', 'Efficiency and Optimization', 'Training Techniques', 'Has Code']
---
Recent advancements in LLM pretraining have featured ever-expanding context
windows to process longer sequences. However, our pilot study reveals that
models pretrained with shorter context windows consistently outperform their
long-context counterparts under a fixed token budget. This finding motivates us
to explore an optimal context window scheduling strategy to better balance
long-context capability with pretraining efficiency. To this end, we propose
SkyLadder, a simple yet effective approach that implements a short-to-long
context window transition. SkyLadder preserves strong standard benchmark
performance, while matching or exceeding baseline results on long context
tasks. Through extensive experiments, we pre-train 1B-parameter models (up to
32K context) and 3B-parameter models (8K context) on 100B tokens, demonstrating
that SkyLadder yields consistent gains of up to 3.7% on common benchmarks,
while achieving up to 22% faster training speeds compared to baselines. The
code is at https://github.com/sail-sg/SkyLadder.
