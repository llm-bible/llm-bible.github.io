---
layout: publication
title: 'Does Reasoning Introduce Bias? A Study Of Social Bias Evaluation And Mitigation In LLM Reasoning'
authors: Xuyang Wu, Jinming Nian, Ting-ruen Wei, Zhiqiang Tao, Hsin-tai Wu, Yi Fang
conference: "Arxiv"
year: 2025
bibkey: wu2025does
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.15361'}
tags: ['Ethics and Bias', 'GPT', 'Model Architecture']
---
Recent advances in large language models (LLMs) have enabled automatic generation of chain-of-thought (CoT) reasoning, leading to strong performance on tasks such as math and code. However, when reasoning steps reflect social stereotypes (e.g., those related to gender, race or age), they can reinforce harmful associations and lead to misleading conclusions. We present the first systematic evaluation of social bias within LLM-generated reasoning, using the BBQ dataset to analyze both prediction accuracy and bias. Our study spans a wide range of mainstream reasoning models, including instruction-tuned and CoT-augmented variants of DeepSeek-R1 (8B/32B), ChatGPT, and other open-source LLMs. We quantify how biased reasoning steps correlate with incorrect predictions and often lead to stereotype expression. To mitigate reasoning-induced bias, we propose Answer Distribution as Bias Proxy (ADBP), a lightweight mitigation method that detects bias by tracking how model predictions change across incremental reasoning steps. ADBP outperforms a stereotype-free baseline in most cases, mitigating bias and improving the accuracy of LLM outputs. Code will be released upon paper acceptance.
