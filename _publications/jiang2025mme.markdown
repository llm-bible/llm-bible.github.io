---
layout: publication
title: 'Mme-cot: Benchmarking Chain-of-thought In Large Multimodal Models For Reasoning Quality, Robustness, And Efficiency'
authors: Dongzhi Jiang, Renrui Zhang, Ziyu Guo, Yanwei Li, Yu Qi, Xinyan Chen, Liuhui Wang, Jianhan Jin, Claire Guo, Shen Yan, Bo Zhang, Chaoyou Fu, Peng Gao, Hongsheng Li
conference: "Arxiv"
year: 2025
bibkey: jiang2025mme
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.09621"}
tags: ['Efficiency and Optimization', 'GPT', 'RAG', 'Model Architecture', 'Security', 'Multimodal Models', 'Prompting']
---
Answering questions with Chain-of-Thought (CoT) has significantly enhanced
the reasoning capabilities of Large Language Models (LLMs), yet its impact on
Large Multimodal Models (LMMs) still lacks a systematic assessment and in-depth
investigation. In this paper, we introduce MME-CoT, a specialized benchmark
evaluating the CoT reasoning performance of LMMs, spanning six domains: math,
science, OCR, logic, space-time, and general scenes. As the first comprehensive
study in this area, we propose a thorough evaluation suite incorporating three
novel metrics that assess the reasoning quality, robustness, and efficiency at
a fine-grained level. Leveraging curated high-quality data and a unique
evaluation strategy, we conduct an in-depth analysis of state-of-the-art LMMs,
uncovering several key insights: 1) Models with reflection mechanism
demonstrate a superior CoT quality, with Kimi k1.5 outperforming GPT-4o and
demonstrating the highest quality results; 2) CoT prompting often degrades LMM
performance on perception-heavy tasks, suggesting a potentially harmful
overthinking behavior; and 3) Although the CoT quality is high, LMMs with
reflection exhibit significant inefficiency in both normal response and
self-correction phases. We hope MME-CoT serves as a foundation for advancing
multimodal reasoning in LMMs. Project Page: https://mmecot.github.io/
