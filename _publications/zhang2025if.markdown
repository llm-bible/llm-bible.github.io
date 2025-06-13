---
layout: publication
title: 'If Multi-agent Debate Is The Answer, What Is The Question?'
authors: Hangfan Zhang, Zhiyao Cui, Xinrun Wang, Qiaosheng Zhang, Zhen Wang, Dinghao Wu, Shuyue Hu
conference: "Arxiv"
year: 2025
bibkey: zhang2025if
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08788"}
tags: ['Agentic', 'Tools', 'Reinforcement Learning']
---
Multi-agent debate (MAD) has emerged as a promising approach to enhance the
factual accuracy and reasoning quality of large language models (LLMs) by
engaging multiple agents in iterative discussions during inference. Despite its
potential, we argue that current MAD research suffers from critical
shortcomings in evaluation practices, including limited dataset overlap and
inconsistent baselines, raising significant concerns about generalizability.
Correspondingly, this paper presents a systematic evaluation of five
representative MAD methods across nine benchmarks using four foundational
models. Surprisingly, our findings reveal that MAD methods fail to reliably
outperform simple single-agent baselines such as Chain-of-Thought and
Self-Consistency, even when consuming additional inference-time computation.
From our analysis, we found that model heterogeneity can significantly improve
MAD frameworks. We propose Heter-MAD enabling a single LLM agent to access the
output from heterogeneous foundation models, which boosts the performance of
current MAD frameworks. Finally, we outline potential directions for advancing
MAD, aiming to spark a broader conversation and inspire future work in this
area.
