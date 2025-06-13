---
layout: publication
title: 'Hierarchical Safety Realignment: Lightweight Restoration Of Safety In Pruned Large Vision-language Models'
authors: Yue Li, Xin Yi, Dongsheng Shi, Gerard De Melo, Xiaoling Wang, Linlin Wang
conference: "Arxiv"
year: 2025
bibkey: li2025hierarchical
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16104'}
tags: ['Attention Mechanism', 'Efficiency and Optimization', 'Model Architecture', 'Pruning', 'Multimodal Models', 'Responsible AI']
---
With the increasing size of Large Vision-Language Models (LVLMs), network pruning techniques aimed at compressing models for deployment in resource-constrained environments have garnered significant attention. However, we observe that pruning often leads to a degradation in safety performance. To address this issue, we present a novel and lightweight approach, termed Hierarchical Safety Realignment (HSR). HSR operates by first quantifying the contribution of each attention head to safety, identifying the most critical ones, and then selectively restoring neurons directly within these attention heads that play a pivotal role in maintaining safety. This process hierarchically realigns the safety of pruned LVLMs, progressing from the attention head level to the neuron level. We validate HSR across various models and pruning strategies, consistently achieving notable improvements in safety performance. To our knowledge, this is the first work explicitly focused on restoring safety in LVLMs post-pruning.
