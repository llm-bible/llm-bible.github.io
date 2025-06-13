---
layout: publication
title: 'Not Everything Is All You Need: Toward Low-redundant Optimization For Large Language Model Alignment'
authors: Zhipeng Chen, Kun Zhou, Wayne Xin Zhao, Jingyuan Wang, Ji-rong Wen
conference: "Arxiv"
year: 2024
bibkey: chen2024not
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12606"}
  - {name: "Code", url: "https://github.com/RUCAIBox/ALLO"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Has Code', 'Reinforcement Learning']
---
Large language models (LLMs) are still struggling in aligning with human
preference in complex tasks and scenarios. They are prone to overfit into the
unexpected patterns or superficial styles in the training data. We conduct an
empirical study that only selects the top-10% most updated parameters in LLMs
for alignment training, and see improvements in the convergence process and
final performance. It indicates the existence of redundant neurons in LLMs for
alignment training. To reduce its influence, we propose a low-redundant
alignment method named \textbf\{ALLO\}, focusing on optimizing the most related
neurons with the most useful supervised signals. Concretely, we first identify
the neurons that are related to the human preference data by a gradient-based
strategy, then identify the alignment-related key tokens by reward models for
computing loss. Besides, we also decompose the alignment process into the
forgetting and learning stages, where we first forget the tokens with unaligned
knowledge and then learn aligned knowledge, by updating different ratios of
neurons, respectively. Experimental results on 10 datasets have shown the
effectiveness of ALLO. Our code and data are available at
\url\{https://github.com/RUCAIBox/ALLO\}.
