---
layout: publication
title: 'Not All Attention Is Needed: Parameter And Computation Efficient Transfer Learning For Multi-modal Large Language Models'
authors: Wu Qiong, Ye Weihao, Zhou Yiyi, Sun Xiaoshuai, Ji Rongrong
conference: "Arxiv"
year: 2024
bibkey: wu2024not
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.15226"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture']
---
In this paper we propose a novel parameter and computation efficient tuning method for Multi-modal Large Language Models (MLLMs) termed Efficient Attention Skipping (EAS). Concretely we first reveal that multi-head attentions (MHAs) the main computational overhead of MLLMs are often redundant to downstream tasks. Based on this observation EAS evaluates the attention redundancy and skips the less important MHAs to speed up inference. Besides we also propose a novel propagation-of-information adapter (PIA) to serve the attention skipping of EAS and keep parameter efficiency which can be further re-parameterized into feed-forward networks (FFNs) for zero-extra latency. To validate EAS we apply it to a recently proposed MLLM called LaVIN and a classic VL pre-trained model called METER and conduct extensive experiments on a set of benchmarks. The experiments show that EAS not only retains high performance and parameter efficiency but also greatly speeds up inference speed. For instance LaVIN-EAS can obtain 89.9837; accuracy on ScineceQA while speeding up inference by 2.2 times to LaVIN
