---
layout: publication
title: 'Cot-uq: Improving Response-wise Uncertainty Quantification In Llms With Chain-of-thought'
authors: Boxuan Zhang, Ruqi Zhang
conference: "Arxiv"
year: 2025
bibkey: zhang2025cot
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.17214"}
  - {name: "Code", url: "https://github.com/ZBox1005/CoT-UQ"}
tags: ['Tools', 'RAG', 'Reinforcement Learning', 'Has Code', 'Prompting']
---
Large language models (LLMs) excel in many tasks but struggle to accurately quantify uncertainty in their generated responses. This limitation makes it challenging to detect misinformation and ensure reliable decision-making. Existing uncertainty quantification (UQ) methods for LLMs are primarily prompt-wise rather than response-wise, often requiring multiple response samples, which incurs high computational costs. Moreover, LLMs have been shown to be overconfident, particularly when using reasoning steps to derive their answers. In this work, we propose CoT-UQ, a response-wise UQ framework that integrates LLMs' inherent reasoning capabilities through Chain-of-Thought (CoT) into the UQ process. CoT-UQ captures critical information during inference by extracting keywords from each reasoning step and assessing their importance to the final answer. This key reasoning information is then aggregated to produce a final uncertainty estimate. We conduct extensive experiments based on Llama Family with model sizes varying from 8B to 13B across logical and mathematical reasoning tasks. Experimental results demonstrate that CoT-UQ significantly outperforms existing UQ methods, achieving an average improvement of 5.9% AUROC compared to current UQ methods. The code is available at: https://github.com/ZBox1005/CoT-UQ.
