---
layout: publication
title: The Good, The Bad, And The Greedy&#58; Evaluation Of Llms Should Not Ignore Non-determinism
authors: Song Yifan, Wang Guoyin, Li Sujian, Lin Bill Yuchen
conference: "Arxiv"
year: 2024
bibkey: song2024evaluation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10457"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Current evaluations of large language models (LLMs) often overlook non-determinism typically focusing on a single output per example. This limits our understanding of LLM performance variability in real-world applications. Our study addresses this issue by exploring key questions about the performance differences between greedy decoding and sampling identifying benchmarks consistency regarding non-determinism and examining unique model behaviors. Through extensive experiments we observe that greedy decoding generally outperforms sampling methods for most evaluated tasks. We also observe consistent performance across different LLM sizes and alignment methods noting that alignment can reduce sampling variance. Moreover our best-of-N sampling approach demonstrates that smaller LLMs can match or surpass larger models such as GPT-4-Turbo highlighting the untapped potential of smaller LLMs. This research shows the importance of considering non-determinism in LLM evaluations and provides insights for future LLM development and evaluation.
