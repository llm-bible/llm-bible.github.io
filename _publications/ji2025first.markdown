---
layout: publication
title: 'The First Few Tokens Are All You Need: An Efficient And Effective Unsupervised Prefix Fine-tuning Method For Reasoning Models'
authors: Ke Ji, Jiahao Xu, Tian Liang, Qiuzhi Liu, Zhiwei He, Xingyu Chen, Xiaoyuan Liu, Zhijie Wang, Junying Chen, Benyou Wang, Zhaopeng Tu, Haitao Mi, Dong Yu
conference: "Arxiv"
year: 2025
bibkey: ji2025first
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.02875"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Improving the reasoning capabilities of large language models (LLMs)
typically requires supervised fine-tuning with labeled data or computationally
expensive sampling. We introduce Unsupervised Prefix Fine-Tuning (UPFT), which
leverages the observation of Prefix Self-Consistency -- the shared initial
reasoning steps across diverse solution trajectories -- to enhance LLM
reasoning efficiency. By training exclusively on the initial prefix substrings
(as few as 8 tokens), UPFT removes the need for labeled data or exhaustive
sampling. Experiments on reasoning benchmarks show that UPFT matches the
performance of supervised methods such as Rejection Sampling Fine-Tuning, while
reducing training time by 75% and sampling cost by 99%. Further analysis
reveals that errors tend to appear in later stages of the reasoning process and
that prefix-based training preserves the model's structural knowledge. This
work demonstrates how minimal unsupervised fine-tuning can unlock substantial
reasoning gains in LLMs, offering a scalable and resource-efficient alternative
to conventional approaches.
