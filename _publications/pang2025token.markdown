---
layout: publication
title: 'Token Cleaning: Fine-grained Data Selection For LLM Supervised Fine-tuning'
authors: Jinlong Pang, Na Di, Zhaowei Zhu, Jiaheng Wei, Hao Cheng, Chen Qian, Yang Liu
conference: "Arxiv"
year: 2025
bibkey: pang2025token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01968"}
tags: ['Fine-Tuning', 'Pre-Training', 'Tools', 'Training Techniques', 'Pretraining Methods']
---
Recent studies show that in supervised fine-tuning (SFT) of large language
models (LLMs), data quality matters more than quantity. While most data
cleaning methods concentrate on filtering entire samples, the quality of
individual tokens within a sample can vary significantly. After pre-training,
even in high-quality samples, patterns or phrases that are not task-related can
be redundant or uninformative. Continuing to fine-tune on these patterns may
offer limited benefit and even degrade downstream task performance. In this
paper, we investigate token quality from a noisy-label perspective and propose
a generic token cleaning pipeline for SFT tasks. Our method filters out
uninformative tokens while preserving those carrying key task-specific
information. Specifically, we first evaluate token quality by examining the
influence of model updates on each token, then apply a threshold-based
separation. The token influence can be measured in a single pass with a fixed
reference model or iteratively with self-evolving reference models. The
benefits and limitations of both methods are analyzed theoretically by error
upper bounds. Extensive experiments show that our framework consistently
improves performance across multiple downstream tasks.
