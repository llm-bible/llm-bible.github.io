---
layout: publication
title: 'Walledeval: A Comprehensive Safety Evaluation Toolkit For Large Language Models'
authors: Prannaya Gupta, Le Qi Yau, Hao Han Low, I-shiang Lee, Hugo Maximus Lim, Yu Xin Teoh, Jia Hng Koh, Dar Win Liew, Rishabh Bhardwaj, Rajat Bhardwaj, Soujanya Poria
conference: "Arxiv"
year: 2024
bibkey: gupta2024comprehensive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.03837'}
  - {name: "Code", url: 'https://github.com/walledai/walledeval'}
tags: ['Has Code', 'Tools', 'Prompting', 'Reinforcement Learning', 'Responsible AI']
---
WalledEval is a comprehensive AI safety testing toolkit designed to evaluate
large language models (LLMs). It accommodates a diverse range of models,
including both open-weight and API-based ones, and features over 35 safety
benchmarks covering areas such as multilingual safety, exaggerated safety, and
prompt injections. The framework supports both LLM and judge benchmarking and
incorporates custom mutators to test safety against various text-style
mutations, such as future tense and paraphrasing. Additionally, WalledEval
introduces WalledGuard, a new, small, and performant content moderation tool,
and two datasets: SGXSTest and HIXSTest, which serve as benchmarks for
assessing the exaggerated safety of LLMs and judges in cultural contexts. We
make WalledEval publicly available at https://github.com/walledai/walledeval.
