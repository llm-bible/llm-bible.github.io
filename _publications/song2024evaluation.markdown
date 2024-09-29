---
layout: publication
title: The Good The Bad And The Greedy Evaluation Of Llms Should Not Ignore Non45;determinism
authors: Song Yifan, Wang Guoyin, Li Sujian, Lin Bill Yuchen
conference: "Arxiv"
year: 2024
bibkey: song2024evaluation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10457"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Current evaluations of large language models (LLMs) often overlook non45;determinism typically focusing on a single output per example. This limits our understanding of LLM performance variability in real45;world applications. Our study addresses this issue by exploring key questions about the performance differences between greedy decoding and sampling identifying benchmarks consistency regarding non45;determinism and examining unique model behaviors. Through extensive experiments we observe that greedy decoding generally outperforms sampling methods for most evaluated tasks. We also observe consistent performance across different LLM sizes and alignment methods noting that alignment can reduce sampling variance. Moreover our best45;of45;N sampling approach demonstrates that smaller LLMs can match or surpass larger models such as GPT45;445;Turbo highlighting the untapped potential of smaller LLMs. This research shows the importance of considering non45;determinism in LLM evaluations and provides insights for future LLM development and evaluation.
