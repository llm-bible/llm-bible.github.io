---
layout: publication
title: 'Kaft: Knowledge-aware Fine-tuning For Boosting Llms'' Domain-specific Question-answering Performance'
authors: Qihuang Zhong, Liang Ding, Xiantao Cai, Juhua Liu, Bo Du, Dacheng Tao
conference: "Arxiv"
year: 2025
bibkey: zhong2025knowledge
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.15480'}
tags: ['Reinforcement Learning', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Supervised fine-tuning (SFT) is a common approach to improve the domain-specific question-answering (QA) performance of large language models (LLMs). However, recent literature reveals that due to the conflicts between LLMs' internal knowledge and the context knowledge of training data, vanilla SFT using the full QA training set is usually suboptimal. In this paper, we first design a query diversification strategy for robust conflict detection and then conduct a series of experiments to analyze the impact of knowledge conflict. We find that 1) training samples with varied conflicts contribute differently, where SFT on the data with large conflicts leads to catastrophic performance drops; 2) compared to directly filtering out the conflict data, appropriately applying the conflict data would be more beneficial. Motivated by this, we propose a simple-yet-effective Knowledge-aware Fine-tuning (namely KaFT) approach to effectively boost LLMs' performance. The core of KaFT is to adapt the training weight by assigning different rewards for different training samples according to conflict level. Extensive experiments show that KaFT brings consistent and significant improvements across four LLMs. More analyses prove that KaFT effectively improves the model generalization and alleviates the hallucination.
