---
layout: publication
title: 'Safe At The Margins: A General Approach To Safety Alignment In Low-resource English Languages -- A Singlish Case Study'
authors: Isaac Lim, Shaun Khoo, Roy Ka-wei Lee, Watson Chua, Jia Yi Goh, Jessica Foo
conference: "Arxiv"
year: 2025
bibkey: lim2025safe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12485"}
tags: ['Responsible AI', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
Ensuring the safety of Large Language Models (LLMs) in diverse linguistic
settings remains challenging, particularly for low-resource languages. Existing
safety alignment methods are English-centric, limiting their effectiveness. We
systematically compare Supervised Fine-Tuning (SFT), Direct Preference
Optimization (DPO), and Kahneman-Tversky Optimization (KTO) for aligning
SEA-Lion-v2.1-Instruct, a Llama 3-8B variant, to reduce toxicity in Singlish.
Our results show that SFT+KTO achieves superior safety alignment with higher
sample efficiency than DPO. Additionally, we introduce KTO-S, which enhances
stability via improved KL divergence regularization. Our approach reduces
Singlish toxicity by 99%, generalizes to TOXIGEN, and maintains strong
performance on standard LLM benchmarks, providing a scalable framework for
safer AI deployment in multilingual contexts.
