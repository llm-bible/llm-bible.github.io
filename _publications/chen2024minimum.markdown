---
layout: publication
title: 'Minimum Tuning To Unlock Long Output From Llms With High Quality Data As The Key'
authors: Yingda Chen, Xingjun Wang, Jintao Huang, Yunlin Mao, Daoze Zhang, Yuze Zhao
conference: "Arxiv"
year: 2024
bibkey: chen2024minimum
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.10210'}
tags: ['Reinforcement Learning', 'Tools', 'Training Techniques']
---
As large language models rapidly evolve to support longer context, there is a
notable disparity in their capability to generate output at greater lengths.
Recent study suggests that the primary cause for this imbalance may arise from
the lack of data with long-output during alignment training. In light of this
observation, attempts are made to re-align foundation models with data that
fills the gap, which result in models capable of generating lengthy output when
instructed. In this paper, we explore the impact of data-quality in tuning a
model for long output, and the possibility of doing so from the starting points
of human-aligned (instruct or chat) models. With careful data curation, we show
that it possible to achieve similar performance improvement in our tuned
models, with only a small fraction of training data instances and compute. In
addition, we assess the generalizability of such approaches by applying our
tuning-recipes to several models. our findings suggest that, while capacities
for generating long output vary across different models out-of-the-box, our
approach to tune them with high-quality data using lite compute, consistently
yields notable improvement across all models we experimented on. We have made
public our curated dataset for tuning long-writing capability, the
implementations of model tuning and evaluation, as well as the fine-tuned
models, all of which can be openly-accessed.
