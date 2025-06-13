---
layout: publication
title: 'Focusllava: A Coarse-to-fine Approach For Efficient And Effective Visual Token Compression'
authors: Yuke Zhu, Chi Xie, Shuang Liang, Bo Zheng, Sheng Guo
conference: "Arxiv"
year: 2024
bibkey: zhu2024coarse
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.14228'}
tags: ['Efficiency and Optimization']
---
Recent advances on Multi-modal Large Language Models have demonstrated that
high-resolution image input is crucial for model capabilities, especially for
fine-grained tasks. However, high-resolution images lead to a quadratic
increase in the number of visual tokens input into LLMs, resulting in
significant computational costs. Current work develop visual token compression
methods to achieve efficiency improvements, often at the expense of
performance. We argue that removing visual redundancy can simultaneously
improve both efficiency and performance. We build a coarse-to-fine visual token
compression method, with a vision-guided sampler for compressing redundant
regions with low information density, and a text-guided sampler for selecting
visual tokens that are strongly correlated with the user instructions.With
these two modules, the proposed FocusLLaVA achieves improvements in both
efficiency and performance. We validate the effectiveness of our approach on a
wide range of evaluation datasets.
