---
layout: publication
title: 'Factual Inconsistency In Data-to-text Generation Scales Exponentially With LLM Size: A Statistical Validation'
authors: Joy Mahapatra, Soumyajit Roy, Utpal Garain
conference: "Arxiv"
year: 2025
bibkey: mahapatra2025factual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.12372'}
tags: ['Large-Scale Training', 'Language Modeling', 'Efficiency and Optimization', 'Tools', 'Scaling Laws', 'Model Architecture', 'Applications', 'Pre-Training']
---
Monitoring factual inconsistency is essential for ensuring trustworthiness in
data-to-text generation (D2T). While large language models (LLMs) have
demonstrated exceptional performance across various D2T tasks, previous studies
on scaling laws have primarily focused on generalization error through power
law scaling to LLM size (i.e., the number of model parameters). However, no
research has examined the impact of LLM size on factual inconsistency in D2T.
In this paper, we investigate how factual inconsistency in D2T scales with LLM
size by exploring two scaling laws: power law and exponential scaling. To
rigorously evaluate and compare these scaling laws, we employ a statistical
validation framework consisting of three key stages: predictive performance
estimation, goodness-of-fit assessment, and comparative analysis. For a
comprehensive empirical study, we analyze three popular LLM families across
five D2T datasets, measuring factual inconsistency inversely using four
state-of-the-art consistency metrics. Our findings, based on exhaustive
empirical results and validated through our framework, reveal that, contrary to
the widely assumed power law scaling, factual inconsistency in D2T follows an
exponential scaling with LLM size.
