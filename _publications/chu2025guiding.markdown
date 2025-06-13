---
layout: publication
title: 'Domaino1s: Guiding LLM Reasoning For Explainable Answers In High-stakes Domains'
authors: Xu Chu, Zhijie Tan, Hanlin Xue, Guanyu Wang, Tong Mo, Weiping Li
conference: "Arxiv"
year: 2025
bibkey: chu2025guiding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.14431'}
  - {name: "Code", url: 'https://github.com/Hyalinesky/Domaino1s'}
tags: ['Has Code', 'Interpretability and Explainability', 'Training Techniques', 'Fine-Tuning', 'Interpretability', 'Pretraining Methods']
---
Large Language Models (LLMs) are widely applied to downstream domains. However, current LLMs for high-stakes domain tasks, such as financial investment and legal QA, typically generate brief answers without reasoning processes and explanations. This limits users' confidence in making decisions based on their responses. While original CoT shows promise, it lacks self-correction mechanisms during reasoning. This work introduces Domain\\(o1\\)s, which enhances LLMs' reasoning capabilities on domain tasks through supervised fine-tuning and tree search. We construct CoT-stock-2k and CoT-legal-2k datasets for fine-tuning models that activate domain-specific reasoning steps based on their judgment. Additionally, we propose Selective Tree Exploration to spontaneously explore solution spaces and sample optimal reasoning paths to improve performance. We also introduce PROOF-Score, a new metric for evaluating domain models' explainability, complementing traditional accuracy metrics with richer assessment dimensions. Extensive experiments on stock investment recommendation and legal reasoning QA tasks demonstrate Domaino1s's leading performance and explainability. Our code is available at https://github.com/Hyalinesky/Domaino1s.
