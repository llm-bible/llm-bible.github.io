---
layout: publication
title: 'Investigating And Scaling Up Code-switching For Multilingual Language Model Pre-training'
authors: Zhijun Wang, Jiahuan Li, Hao Zhou, Rongxiang Weng, Jingang Wang, Xin Huang, Xue Han, Junlan Feng, Chao Deng, Shujian Huang
conference: "Arxiv"
year: 2025
bibkey: wang2025investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.01801"}
tags: ['Training Techniques', 'Pre-Training']
---
Large language models (LLMs) exhibit remarkable multilingual capabilities
despite the extreme language imbalance in the pre-training data. In this paper,
we closely examine the reasons behind this phenomenon, focusing on the
pre-training corpus. We find that the existence of code-switching, alternating
between different languages within a context, is key to multilingual
capabilities. We conduct an analysis to investigate code-switching in the
pre-training corpus, examining its presence and categorizing it into four types
within two quadrants. We then assess its impact on multilingual performance.
These types of code-switching data are unbalanced in proportions and
demonstrate different effects on facilitating language transfer. To better
explore the power of code-switching for language alignment during pre-training,
we investigate the strategy of synthetic code-switching. We continuously scale
up the synthetic code-switching data and observe remarkable improvements in
both benchmarks and representation space. Extensive experiments indicate that
incorporating synthetic code-switching data enables better language alignment
and generalizes well to high, medium, and low-resource languages with
pre-training corpora of varying qualities.
