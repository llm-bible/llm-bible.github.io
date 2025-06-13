---
layout: publication
title: 'Aligning Instruction Tuning With Pre-training'
authors: Yiming Liang, Tianyu Zheng, Xinrun Du, Ge Zhang, Jiaheng Liu, Xingwei Qu, Wenqiang Zu, Xingrun Xing, Chujie Zheng, Lei Ma, Wenhu Chen, Guoyin Wang, Zhaoxiang Zhang, Wenhao Huang, Xiang Yue, Jiajun Zhang
conference: "Arxiv"
year: 2025
bibkey: liang2025aligning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.09368'}
tags: ['RAG', 'Fine-Tuning', 'Training Techniques', 'Pre-Training']
---
Instruction tuning enhances large language models (LLMs) to follow human
instructions across diverse tasks, relying on high-quality datasets to guide
behavior. However, these datasets, whether manually curated or synthetically
generated, are often narrowly focused and misaligned with the broad
distributions captured during pre-training, limiting LLM generalization and
effective use of pre-trained knowledge. We propose Aligning Instruction Tuning
with Pre-training (AITP), a method that bridges this gap by identifying
coverage shortfalls in instruction-tuning datasets and rewriting
underrepresented pre-training data into high-quality instruction-response
pairs. This approach enriches dataset diversity while preserving task-specific
objectives. Evaluations on three fully open LLMs across eight benchmarks
demonstrate consistent performance improvements with AITP. Ablations highlight
the benefits of adaptive data selection, controlled rewriting, and balanced
integration, emphasizing the importance of aligning instruction tuning with
pre-training distributions to unlock the full potential of LLMs.
