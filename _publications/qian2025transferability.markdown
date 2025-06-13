---
layout: publication
title: 'Fino1: On The Transferability Of Reasoning Enhanced Llms To Finance'
authors: Lingfei Qian, Weipeng Zhou, Yan Wang, Xueqing Peng, Han Yi, Jimin Huang, Qianqian Xie, Jianyun Nie
conference: "Arxiv"
year: 2025
bibkey: qian2025transferability
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08127"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
While large language models (LLMs) have shown strong general reasoning
capabilities, their effectiveness in financial reasoning, which is crucial for
real-world financial applications remains underexplored. In this study, we
conduct a comprehensive evaluation of 24 state-of-the-art general and
reasoning-focused LLMs across four complex financial reasoning tasks involving
financial text, tabular data, and equations. We assess key capabilities such as
numerical reasoning, tabular interpretation, financial terminology
comprehension, long-context understanding, and equation-based problem solving.
Our analysis reveals that while data quality and pretraining contribute to
performance, general techniques like chain-of-thought (CoT) fine-tuning offer
limited gains in financial tasks. To address this, we propose two
domain-adapted models, Fino1-8B and Fino1-14B, trained with CoT fine-tuning and
reinforcement learning using domain-specific reasoning paths. Our models are
trained on a carefully curated dataset integrating high-quality examples from
diverse sources, covering financial reports, tables, equations, and structured
XBRL texts. Despite limited training data, they achieve an 7-9% performance
improvement, outperforming several advanced LLMs, including GPT-o1,
GPT-o3-mini, GPT-4.5, and comparable with DeepSeek models (V3 and R1),
demonstrating strong practical value in resource, constrained scenarios. Our
findings highlight the need for domain-specific adaptations in financial
reasoning, and we release all datasets, models, and code for future research.
