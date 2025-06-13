---
layout: publication
title: 'Harmony In Divergence: Towards Fast, Accurate, And Memory-efficient Zeroth-order LLM Fine-tuning'
authors: Qitao Tan, Jun Liu, Zheng Zhan, Caiwei Ding, Yanzhi Wang, Jin Lu, Geng Yuan
conference: "Arxiv"
year: 2025
bibkey: tan2025harmony
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.03304"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'BERT']
---
Large language models (LLMs) excel across various tasks, but standard
first-order (FO) fine-tuning demands considerable memory, significantly
limiting real-world deployment. Recently, zeroth-order (ZO) optimization stood
out as a promising memory-efficient training paradigm, avoiding backward passes
and relying solely on forward passes for gradient estimation, making it
attractive for resource-constrained scenarios. However, ZO method lags far
behind FO method in both convergence speed and accuracy. To bridge the gap, we
introduce a novel layer-wise divergence analysis that uncovers the distinct
update pattern of FO and ZO optimization. Aiming to resemble the learning
capacity of FO method from the findings, we propose \textbf\{Di\}vergence-driven
\textbf\{Z\}eroth-\textbf\{O\}rder (\textbf\{DiZO\}) optimization. DiZO conducts
divergence-driven layer adaptation by incorporating projections to ZO updates,
generating diverse-magnitude updates precisely scaled to layer-wise individual
optimization needs. Our results demonstrate that DiZO significantly reduces the
needed iterations for convergence without sacrificing throughput, cutting
training GPU hours by up to 48% on various datasets. Moreover, DiZO
consistently outperforms the representative ZO baselines in fine-tuning
RoBERTa-large, OPT-series, and Llama-series on downstream tasks and, in some
cases, even surpasses memory-intensive FO fine-tuning.
