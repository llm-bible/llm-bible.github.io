---
layout: publication
title: 'Benchmarking And Understanding Compositional Relational Reasoning Of Llms'
authors: Ruikang Ni, Da Xiao, Qingye Meng, Xiangyu Li, Shihui Zheng, Hongliang Liang
conference: "Arxiv"
year: 2024
bibkey: ni2024benchmarking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.12841'}
  - {name: "Code", url: 'https://github.com/Caiyun-AI/GAR'}
tags: ['Attention Mechanism', 'Has Code', 'Interpretability and Explainability', 'Transformer', 'Model Architecture', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Compositional relational reasoning (CRR) is a hallmark of human intelligence,
but we lack a clear understanding of whether and how existing transformer large
language models (LLMs) can solve CRR tasks. To enable systematic exploration of
the CRR capability of LLMs, we first propose a new synthetic benchmark called
Generalized Associative Recall (GAR) by integrating and generalizing the
essence of several tasks in mechanistic interpretability (MI) study in a
unified framework. Evaluation shows that GAR is challenging enough for existing
LLMs, revealing their fundamental deficiency in CRR. Meanwhile, it is easy
enough for systematic MI study. Then, to understand how LLMs solve GAR tasks,
we use attribution patching to discover the core circuits reused by Vicuna-33B
across different tasks and a set of vital attention heads. Intervention
experiments show that the correct functioning of these heads significantly
impacts task performance. Especially, we identify two classes of heads whose
activations represent the abstract notion of true and false in GAR tasks
respectively. They play a fundamental role in CRR across various models and
tasks. The dataset and code are available at https://github.com/Caiyun-AI/GAR.
