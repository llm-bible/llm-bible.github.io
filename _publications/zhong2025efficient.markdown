---
layout: publication
title: 'Efficient Evaluation Of Large Language Models Via Collaborative Filtering'
authors: Xu-xiang Zhong, Chao Yi, Han-jia Ye
conference: "Arxiv"
year: 2025
bibkey: zhong2025efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.08781'}
tags: ['Uncategorized']
---
With the development of Large Language Models (LLMs), numerous benchmarks
have been proposed to measure and compare the capabilities of different LLMs.
However, evaluating LLMs is costly due to the large number of test instances
and their slow inference speed. In this paper, we aim to explore how to
efficiently estimate a model's real performance on a given benchmark based on
its evaluation results on a small number of instances sampled from the
benchmark. Inspired by Collaborative Filtering (CF) in Recommendation Systems
(RS), we treat LLMs as users and test instances as items and propose a
two-stage method. In the first stage, we treat instance selection as
recommending products to users to choose instances that can easily distinguish
model performance. In the second stage, we see performance prediction as rating
prediction problem in RS to predict the target LLM's behavior on unselected
instances. Experiments on multiple LLMs and datasets imply that our method can
accurately estimate the target model's performance while largely reducing its
inference overhead.
