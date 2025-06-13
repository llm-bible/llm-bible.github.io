---
layout: publication
title: 'Not All Thoughts Are Generated Equal: Efficient LLM Reasoning Via Multi-turn Reinforcement Learning'
authors: Yansong Ning, Wei Li, Jun Fang, Naiqiang Tan, Hao Liu
conference: "Arxiv"
year: 2025
bibkey: ning2025not
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.11827'}
  - {name: "Code", url: 'https://github.com/usail-hkust/LongShort'}
tags: ['Agentic', 'Has Code', 'Efficiency and Optimization', 'Tools', 'Merging', 'Reinforcement Learning']
---
Compressing long chain-of-thought (CoT) from large language models (LLMs) is an emerging strategy to improve the reasoning efficiency of LLMs. Despite its promising benefits, existing studies equally compress all thoughts within a long CoT, hindering more concise and effective reasoning. To this end, we first investigate the importance of different thoughts by examining their effectiveness and efficiency in contributing to reasoning through automatic long CoT chunking and Monte Carlo rollouts. Building upon the insights, we propose a theoretically bounded metric to jointly measure the effectiveness and efficiency of different thoughts. We then propose Long\\(\otimes\\)Short, an efficient reasoning framework that enables two LLMs to collaboratively solve the problem: a long-thought LLM for more effectively generating important thoughts, while a short-thought LLM for efficiently generating remaining thoughts. Specifically, we begin by synthesizing a small amount of cold-start data to fine-tune LLMs for long-thought and short-thought reasoning styles, respectively. Furthermore, we propose a synergizing-oriented multi-turn reinforcement learning, focusing on the model self-evolution and collaboration between long-thought and short-thought LLMs. Experimental results show that our method enables Qwen2.5-7B and Llama3.1-8B to achieve comparable performance compared to DeepSeek-R1-Distill-Qwen-7B and DeepSeek-R1-Distill-Llama-8B, while reducing token length by over 80% across the MATH500, AIME24/25, AMC23, and GPQA Diamond benchmarks. Our data and code are available at https://github.com/usail-hkust/LongShort.
