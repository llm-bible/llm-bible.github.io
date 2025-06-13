---
layout: publication
title: 'Who Reasons In The Large Language Models?'
authors: Jie Shao, Jianxin Wu
conference: "Arxiv"
year: 2025
bibkey: shao2025who
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20993'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'Transformer', 'Model Architecture', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods']
---
Despite the impressive performance of large language models (LLMs), the process of endowing them with new capabilities--such as mathematical reasoning--remains largely empirical and opaque. A critical open question is whether reasoning abilities stem from the entire model, specific modules, or are merely artifacts of overfitting. In this work, we hypothesize that the reasoning capabilities in well-trained LLMs are primarily attributed to the output projection module (oproj) in the Transformer's multi-head self-attention (MHSA) mechanism. To support this hypothesis, we introduce Stethoscope for Networks (SfN), a suite of diagnostic tools designed to probe and analyze the internal behaviors of LLMs. Using SfN, we provide both circumstantial and empirical evidence suggesting that oproj plays a central role in enabling reasoning, whereas other modules contribute more to fluent dialogue. These findings offer a new perspective on LLM interpretability and open avenues for more targeted training strategies, potentially enabling more efficient and specialized LLMs.
