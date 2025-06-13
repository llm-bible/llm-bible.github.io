---
layout: publication
title: 'Brite: Bootstrapping Reinforced Thinking Process To Enhance Language Model Reasoning'
authors: Han Zhong, Yutong Yin, Shenao Zhang, Xiaojun Xu, Yuanxin Liu, Yifei Zuo, Zhihan Liu, Boyi Liu, Sirui Zheng, Hongyi Guo, Liwei Wang, Mingyi Hong, Zhaoran Wang
conference: "Arxiv"
year: 2025
bibkey: zhong2025bootstrapping
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.18858"}
tags: ['Fine-Tuning', 'Agentic', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities in
complex reasoning tasks, yet generating reliable reasoning processes remains a
significant challenge. We present a unified probabilistic framework that
formalizes LLM reasoning through a novel graphical model incorporating latent
thinking processes and evaluation signals. Within this framework, we introduce
the Bootstrapping Reinforced Thinking Process (BRiTE) algorithm, which works in
two steps. First, it generates high-quality rationales by approximating the
optimal thinking process through reinforcement learning, using a novel reward
shaping mechanism. Second, it enhances the base LLM by maximizing the joint
probability of rationale generation with respect to the model's parameters.
Theoretically, we demonstrate BRiTE's convergence at a rate of \\(1/T\\) with \\(T\\)
representing the number of iterations. Empirical evaluations on math and coding
benchmarks demonstrate that our approach consistently improves performance
across different base models without requiring human-annotated thinking
processes. In addition, BRiTE demonstrates superior performance compared to
existing algorithms that bootstrap thinking processes use alternative methods
such as rejection sampling, and can even match or exceed the results achieved
through supervised fine-tuning with human-annotated data.
