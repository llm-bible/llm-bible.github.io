---
layout: publication
title: '1.4 Million Open-source Distilled Reasoning Dataset To Empower Large Language Model Training'
authors: Han Zhao, Haotian Wang, Yiping Peng, Sitong Zhao, Xiaoyu Tian, Shuaiting Chen, Yunjie Ji, Xiangang Li
conference: "Arxiv"
year: 2025
bibkey: zhao2025million
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.19633'}
  - {name: "Code", url: 'https://huggingface.co/datasets/a-m-team/AM-DeepSeek-R1-Distilled-1.4M}{https://huggingface.co/datasets/a-m-team/AM-DeepSeek-R1-Distilled-1.4M'}
tags: ['Has Code', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
The AM-DeepSeek-R1-Distilled is a large-scale dataset with thinking traces
for general reasoning tasks, composed of high-quality and challenging reasoning
problems. These problems are collected from a multitude of open-source
datasets, subjected to semantic deduplication and meticulous cleaning to
eliminate test set contamination. All responses within the dataset are
distilled from reasoning models (predominantly DeepSeek-R1) and have undergone
rigorous verification procedures. Mathematical problems are validated by
checking against reference answers, code problems are verified using test
cases, and other tasks are evaluated with the aid of a reward model. The
AM-Distill-Qwen-32B model, which was trained through only simple Supervised
Fine-Tuning (SFT) using this batch of data, outperformed the
DeepSeek-R1-Distill-Qwen-32B model on four benchmarks: AIME2024, MATH-500,
GPQA-Diamond, and LiveCodeBench. Additionally, the AM-Distill-Qwen-72B model
surpassed the DeepSeek-R1-Distill-Llama-70B model on all benchmarks as well. We
are releasing these 1.4 million problems and their corresponding responses to
the research community with the objective of fostering the development of
powerful reasoning-oriented Large Language Models (LLMs). The dataset was
published in
\href\{https://huggingface.co/datasets/a-m-team/AM-DeepSeek-R1-Distilled-1.4M\}\{https://huggingface.co/datasets/a-m-team/AM-DeepSeek-R1-Distilled-1.4M\}.
