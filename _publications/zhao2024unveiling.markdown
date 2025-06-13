---
layout: publication
title: 'Unveiling In-context Learning: A Coordinate System To Understand Its Working Mechanism'
authors: Anhao Zhao, Fanghua Ye, Jinlan Fu, Xiaoyu Shen
conference: "Arxiv"
year: 2024
bibkey: zhao2024unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.17011"}
tags: ['Tools', 'Prompting', 'In-Context Learning', 'Reinforcement Learning']
---
Large language models (LLMs) exhibit remarkable in-context learning (ICL)
capabilities. However, the underlying working mechanism of ICL remains poorly
understood. Recent research presents two conflicting views on ICL: One
emphasizes the impact of similar examples in the demonstrations, stressing the
need for label correctness and more shots. The other attributes it to LLMs'
inherent ability of task recognition, deeming label correctness and shot
numbers of demonstrations as not crucial. In this work, we provide a
Two-Dimensional Coordinate System that unifies both views into a systematic
framework. The framework explains the behavior of ICL through two orthogonal
variables: whether similar examples are presented in the demonstrations
(perception) and whether LLMs can recognize the task (cognition). We propose
the peak inverse rank metric to detect the task recognition ability of LLMs and
study LLMs' reactions to different definitions of similarity. Based on these,
we conduct extensive experiments to elucidate how ICL functions across each
quadrant on multiple representative classification tasks. Finally, we extend
our analyses to generation tasks, showing that our coordinate system can also
be used to interpret ICL for generation tasks effectively.
