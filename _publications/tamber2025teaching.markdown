---
layout: publication
title: 'Teaching Dense Retrieval Models To Specialize With Listwise Distillation And LLM Data Augmentation'
authors: Manveer Singh Tamber, Suleman Kazi, Vivek Sourabh, Jimmy Lin
conference: "Arxiv"
year: 2025
bibkey: tamber2025teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19712"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Distillation']
---
While the current state-of-the-art dense retrieval models exhibit strong
out-of-domain generalization, they might fail to capture nuanced
domain-specific knowledge. In principle, fine-tuning these models for
specialized retrieval tasks should yield higher effectiveness than relying on a
one-size-fits-all model, but in practice, results can disappoint. We show that
standard fine-tuning methods using an InfoNCE loss can unexpectedly degrade
effectiveness rather than improve it, even for domain-specific scenarios. This
holds true even when applying widely adopted techniques such as hard-negative
mining and negative de-noising. To address this, we explore a training strategy
that uses listwise distillation from a teacher cross-encoder, leveraging rich
relevance signals to fine-tune the retriever. We further explore synthetic
query generation using large language models. Through listwise distillation and
training with a diverse set of queries ranging from natural user searches and
factual claims to keyword-based queries, we achieve consistent effectiveness
gains across multiple datasets. Our results also reveal that synthetic queries
can rival human-written queries in training utility. However, we also identify
limitations, particularly in the effectiveness of cross-encoder teachers as a
bottleneck. We release our code and scripts to encourage further research.
