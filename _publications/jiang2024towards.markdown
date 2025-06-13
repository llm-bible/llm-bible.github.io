---
layout: publication
title: 'Towards Intrinsic Self-correction Enhancement In Monte Carlo Tree Search Boosted Reasoning Via Iterative Preference Learning'
authors: Huchen Jiang, Yangyang Ma, Chaofan Ding, Kexin Luan, Xinhan Di
conference: "Arxiv"
year: 2024
bibkey: jiang2024towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.17397'}
tags: ['Reinforcement Learning', 'RAG', 'Agentic', 'Training Techniques']
---
With current state-of-the-art approaches aimed at enhancing the reasoning
capabilities of Large Language Models(LLMs) through iterative preference
learning inspired by AlphaZero, we propose to further enhance the step-wise
reasoning capabilities through intrinsic self-correction to some extent. Our
work leverages step-wise preference learning to enhance self-verification via
reinforcement learning. We initially conduct our work through a two-stage
training procedure. At the first stage, the self-correction reasoning ability
of an LLM is enhanced through its own predictions, relying entirely on
self-generated data within the intrinsic self-correction to some extent. At the
second stage, the baseline step-wise preference learning is leveraged via the
application of the enhanced self-correct policy achieved at the first stage. In
the evaluation of arithmetic reasoning tasks, our approach outperforms
OpenMath2-Llama3.1-8B, dart-math-mistral-7b-uniform on MATH with increases in
accuracy to 71.34%(+4.18%) and 48.06%(+4.94%) and LLama-3.1-8B-Instruct,
Mistral-7B-Instruct-v0.1 on GSM8K with increases in accuracy to 86.76%(+2.00%)
and 38.06%(+2.28%).
