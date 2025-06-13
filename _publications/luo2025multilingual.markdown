---
layout: publication
title: 'MMATH: A Multilingual Benchmark For Mathematical Reasoning'
authors: Wenyang Luo, Wayne Xin Zhao, Jing Sha, Shijin Wang, Ji-rong Wen
conference: "Arxiv"
year: 2025
bibkey: luo2025multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19126"}
  - {name: "Code", url: "https://github.com/RUCAIBox/MMATH"}
tags: ['Training Techniques', 'Has Code', 'Prompting']
---
The advent of large reasoning models, such as OpenAI o1 and DeepSeek R1, has significantly advanced complex reasoning tasks. However, their capabilities in multilingual complex reasoning remain underexplored, with existing efforts largely focused on simpler tasks like MGSM. To address this gap, we introduce MMATH, a benchmark for multilingual complex reasoning spanning 374 high-quality math problems across 10 typologically diverse languages. Using MMATH, we observe that even advanced models like DeepSeek R1 exhibit substantial performance disparities across languages and suffer from a critical off-target issue-generating responses in unintended languages. To address this, we explore strategies including prompting and training, demonstrating that reasoning in English and answering in target languages can simultaneously enhance performance and preserve target-language consistency. Our findings offer new insights and practical strategies for advancing the multilingual reasoning capabilities of large language models. Our code and data could be found at https://github.com/RUCAIBox/MMATH.
