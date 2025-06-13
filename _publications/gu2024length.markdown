---
layout: publication
title: 'Length Controlled Generation For Black-box Llms'
authors: Yuxuan Gu, Wenjie Wang, Xiaocheng Feng, Weihong Zhong, Kun Zhu, Lei Huang, Tat-seng Chua, Bing Qin
conference: "Arxiv"
year: 2024
bibkey: gu2024length
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14656"}
tags: ['Fine-Tuning', 'Tools', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated impressive instruction
following capabilities, while still struggling to accurately manage the length
of the generated text, which is a fundamental requirement in many real-world
applications. Existing length control methods involve fine-tuning the
parameters of LLMs, which is inefficient and suboptimal for practical use. In
this paper, we propose a novel iterative sampling framework for text length
control, integrating the Metropolis-Hastings algorithm with an importance
sampling acceleration strategy. This framework efficiently and reliably
regulates LLMs to generate length-constrained text without modifying the
underlying parameters, thereby preserving the original capabilities of LLMs.
Experimental results demonstrate that our framework achieves almost 100%
success rates of length control on Llama3.1 for tasks such as length-controlled
abstractive summarization and length-constrained instruction following, with
minimal additional computational overhead. This also highlights the significant
potential of our method for precise length control across a broader range of
applications, without compromising the versatility of LLMs.
