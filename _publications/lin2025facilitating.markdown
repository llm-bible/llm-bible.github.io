---
layout: publication
title: 'Facilitating Long Context Understanding Via Supervised Chain-of-thought Reasoning'
authors: Jingyang Lin, Andy Wong, Tian Xia, Shenghua He, Hui Wei, Mei Han, Jiebo Luo
conference: "Arxiv"
year: 2025
bibkey: lin2025facilitating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13127"}
tags: ['Agentic', 'Model Architecture', 'Tools', 'RAG', 'GPT', 'Interpretability and Explainability', 'Applications']
---
Recent advances in Large Language Models (LLMs) have enabled them to process
increasingly longer sequences, ranging from 2K to 2M tokens and even beyond.
However, simply extending the input sequence length does not necessarily lead
to effective long-context understanding. In this study, we integrate
Chain-of-Thought (CoT) reasoning into LLMs in a supervised manner to facilitate
effective long-context understanding. To achieve this, we introduce
LongFinanceQA, a synthetic dataset in the financial domain designed to improve
long-context reasoning. Unlike existing long-context synthetic data,
LongFinanceQA includes intermediate CoT reasoning before the final conclusion,
which encourages LLMs to perform explicit reasoning, improving accuracy and
interpretability in long-context understanding. To generate synthetic CoT
reasoning, we propose Property-driven Agentic Inference (PAI), an agentic
framework that simulates human-like reasoning steps, including property
extraction, retrieval, and summarization. We evaluate PAI's reasoning
capabilities by assessing GPT-4o-mini w/ PAI on the Loong benchmark,
outperforming standard GPT-4o-mini by 20.0%. Furthermore, we fine-tune
LLaMA-3.1-8B-Instruct on LongFinanceQA, achieving a 24.6% gain on Loong's
financial subset.
