---
layout: publication
title: 'Chain Of Strategy Optimization Makes Large Language Models Better Emotional Supporter'
authors: Weixiang Zhao, Xingyu Sui, Xinyang Han, Yang Deng, Yulin Hu, Jiahe Guo, Libo Qin, Qianyun Du, Shijin Wang, Yanyan Zhao, Bing Qin, Ting Liu
conference: "Arxiv"
year: 2025
bibkey: zhao2025chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.05362"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Bias Mitigation', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning']
---
The growing emotional stress in modern society has increased the demand for
Emotional Support Conversations (ESC). While Large Language Models (LLMs) show
promise for ESC, they face two key challenges: (1) low strategy selection
accuracy, and (2) preference bias, limiting their adaptability to emotional
needs of users. Existing supervised fine-tuning (SFT) struggles to address
these issues, as it rigidly trains models on single gold-standard responses
without modeling nuanced strategy trade-offs. To overcome these limitations, we
propose Chain-of-Strategy Optimization (CSO), a novel approach that optimizes
strategy selection preferences at each dialogue turn. We first leverage Monte
Carlo Tree Search to construct ESC-Pro, a high-quality preference dataset with
turn-level strategy-response pairs. Training on ESC-Pro with CSO improves both
strategy accuracy and bias mitigation, enabling LLMs to generate more
empathetic and contextually appropriate responses. Experiments on LLaMA-3.1-8B,
Gemma-2-9B, and Qwen2.5-7B demonstrate that CSO outperforms standard SFT,
highlighting the efficacy of fine-grained, turn-level preference modeling in
ESC.
