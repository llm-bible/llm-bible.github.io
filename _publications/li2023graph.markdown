---
layout: publication
title: Graph Transformer For Recommendation
authors: Chaoliu Li et al.
conference: Arxiv
year: 2023
citations: 27
bibkey: li2023graph
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.02330'}, {name: Code,
    url: 'https://github.com/HKUDS/GFormer'}]
tags: [Transformer, Training Techniques]
---
This paper presents a novel approach to representation learning in
recommender systems by integrating generative self-supervised learning with
graph transformer architecture. We highlight the importance of high-quality
data augmentation with relevant self-supervised pretext tasks for improving
performance. Towards this end, we propose a new approach that automates the
self-supervision augmentation process through a rationale-aware generative SSL
that distills informative user-item interaction patterns. The proposed
recommender with Graph TransFormer (GFormer) that offers parameterized
collaborative rationale discovery for selective augmentation while preserving
global-aware user-item relationships. In GFormer, we allow the rationale-aware
SSL to inspire graph collaborative filtering with task-adaptive invariant
rationalization in graph transformer. The experimental results reveal that our
GFormer has the capability to consistently improve the performance over
baselines on different datasets. Several in-depth experiments further
investigate the invariant rationale-aware augmentation from various aspects.
The source code for this work is publicly available at:
https://github.com/HKUDS/GFormer.