---
layout: publication
title: 'Samplemix: A Sample-wise Pre-training Data Mixing Strategey By Coordinating Data Quality And Diversity'
authors: Xiangyu Xi, Deyang Kong, Jian Yang, Jiawei Yang, Zhengyu Chen, Wei Wang, Jingang Wang, Xunliang Cai, Shikun Zhang, Wei Ye
conference: "Arxiv"
year: 2025
bibkey: xi2025sample
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01506"}
tags: ['Pretraining Methods', 'Training Techniques', 'Pre-Training', 'Reinforcement Learning']
---
Existing pretraining data mixing methods for large language models (LLMs)
typically follow a domain-wise methodology, a top-down process that first
determines domain weights and then performs uniform data sampling across each
domain. However, these approaches neglect significant inter-domain overlaps and
commonalities, failing to control the global diversity of the constructed
training dataset. Further, uniform sampling within domains ignores fine-grained
sample-specific features, potentially leading to suboptimal data distribution.
To address these shortcomings, we propose a novel sample-wise data mixture
approach based on a bottom-up paradigm. This method performs global
cross-domain sampling by systematically evaluating the quality and diversity of
each sample, thereby dynamically determining the optimal domain distribution.
Comprehensive experiments across multiple downstream tasks and perplexity
assessments demonstrate that SampleMix surpasses existing domain-based methods.
Meanwhile, SampleMix requires 1.4x to 2.1x training steps to achieves the
baselines' performance, highlighting the substantial potential of SampleMix to
optimize pre-training data.
