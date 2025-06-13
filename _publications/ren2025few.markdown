---
layout: publication
title: 'Few-shot LLM Synthetic Data With Distribution Matching'
authors: Jiyuan Ren, Zhaocheng Du, Zhihao Wen, Qinglin Jia, Sunhao Dai, Chuhan Wu, Zhenhua Dong
conference: "Arxiv"
year: 2025
bibkey: ren2025few
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.08661'}
tags: ['Few-Shot', 'Fine-Tuning', 'Tools']
---
As large language models (LLMs) advance, their ability to perform in-context
learning and few-shot language generation has improved significantly. This has
spurred using LLMs to produce high-quality synthetic data to enhance the
performance of smaller models like online retrievers or weak LLMs. However,
LLM-generated synthetic data often differs from the real data in key language
attributes (e.g., styles, tones, content proportions, etc.). As a result,
mixing these synthetic data directly with real data may distort the original
data distribution, potentially hindering performance improvements. To solve
this, we introduce SynAlign: a synthetic data generation and filtering
framework based on key attribute distribution matching. Before generation,
SynAlign employs an uncertainty tracker surrogated by the Gaussian Process
model to iteratively select data clusters distinct from selected ones as
demonstrations for new data synthesis, facilitating the efficient exploration
diversity of the real data. Then, a latent attribute reasoning method is
employed: the LLM summarizes linguistic attributes of demonstrations and then
synthesizes new data based on them. This approach facilitates synthesizing
diverse data with linguistic attributes that appear in real data.After
generation, the Maximum Mean Discrepancy is used as the objective function to
learn the sampling weight of each synthetic data, ensuring distribution
matching with the real data. Our experiments on multiple text prediction tasks
show significant performance improvements. We also conducted an online A/B test
on an online retriever to demonstrate SynAlign's effectiveness.
