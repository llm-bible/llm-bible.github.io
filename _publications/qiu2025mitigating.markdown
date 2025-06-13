---
layout: publication
title: 'DR.GAP: Mitigating Bias In Large Language Models Using Gender-aware Prompting With Demonstration And Reasoning'
authors: Hongye Qiu, Yue Xu, Meikang Qiu, Wenjie Wang
conference: "Arxiv"
year: 2025
bibkey: qiu2025mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11603"}
tags: ['Efficiency and Optimization', 'GPT', 'Ethics and Bias', 'Bias Mitigation', 'Model Architecture', 'Fairness', 'Security', 'Multimodal Models', 'Prompting']
---
Large Language Models (LLMs) exhibit strong natural language processing
capabilities but also inherit and amplify societal biases, including gender
bias, raising fairness concerns. Existing debiasing methods face significant
limitations: parameter tuning requires access to model weights, prompt-based
approaches often degrade model utility, and optimization-based techniques lack
generalizability. To address these challenges, we propose DR.GAP (Demonstration
and Reasoning for Gender-Aware Prompting), an automated and model-agnostic
approach that mitigates gender bias while preserving model performance. DR.GAP
selects bias-revealing examples and generates structured reasoning to guide
models toward more impartial responses. Extensive experiments on coreference
resolution and QA tasks across multiple LLMs (GPT-3.5, Llama3, and
Llama2-Alpaca) demonstrate its effectiveness, generalization ability, and
robustness. DR.GAP can generalize to vision-language models (VLMs), achieving
significant bias reduction.
