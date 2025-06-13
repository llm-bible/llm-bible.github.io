---
layout: publication
title: 'On-policy Self-alignment With Fine-grained Knowledge Feedback For Hallucination Mitigation'
authors: Xueru Wen, Jie Lou, Xinyu Lu, Ji Yuqiu, Xinyan Guan, Yaojie Lu, Hongyu Lin, Ben He, Xianpei Han, Debing Zhang, Le Sun
conference: "Arxiv"
year: 2024
bibkey: wen2024self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.12221'}
tags: ['Reinforcement Learning', 'Agentic', 'Efficiency and Optimization', 'Tools']
---
Hallucination occurs when large language models exhibit behavior that deviates from the boundaries of their knowledge during response generation. To address this critical issue, previous learning-based methods attempt to finetune models but are limited by off-policy sampling and coarse-grained feedback. In this paper, we present \textit\{\b\{R\}einforcement \b\{L\}earning \b\{f\}or \b\{H\}allucination\} (RLFH), an on-policy self-alignment approach that enables LLMs to actively explore their knowledge boundaries and self-correct generation behavior through fine-grained feedback signals. RLFH introduces a self-assessment framework where the policy serves as its own judge. Through this framework, responses are automatically decomposed into atomic facts and their truthfulness and informativeness are assessed against external knowledge sources. The resulting fine-grained feedback at the statement level are then converted into token-level dense reward signals. This enables online reinforcement learning to achieve precise and timely optimization without human intervention. Comprehensive evaluations on HotpotQA, SQuADv2, and Biography benchmarks validate RLFH's effectiveness in hallucination mitigation.
