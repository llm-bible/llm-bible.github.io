---
layout: publication
title: 'Code Needs Comments: Enhancing Code Llms With Comment Augmentation'
authors: Demin Song, Honglin Guo, Yunhua Zhou, Shuhao Xing, Yudong Wang, Zifan Song, Wenwei Zhang, Qipeng Guo, Hang Yan, Xipeng Qiu, Dahua Lin
conference: "Arxiv"
year: 2024
bibkey: song2024code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13013"}
tags: ['Training Techniques', 'Pre-Training', 'Reinforcement Learning']
---
The programming skill is one crucial ability for Large Language Models
(LLMs), necessitating a deep understanding of programming languages (PLs) and
their correlation with natural languages (NLs). We examine the impact of
pre-training data on code-focused LLMs' performance by assessing the comment
density as a measure of PL-NL alignment. Given the scarcity of code-comment
aligned data in pre-training corpora, we introduce a novel data augmentation
method that generates comments for existing code, coupled with a data filtering
strategy that filters out code data poorly correlated with natural language. We
conducted experiments on three code-focused LLMs and observed consistent
improvements in performance on two widely-used programming skill benchmarks.
Notably, the model trained on the augmented data outperformed both the model
used for generating comments and the model further trained on the data without
augmentation.
