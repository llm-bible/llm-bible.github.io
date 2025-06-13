---
layout: publication
title: 'Does Your Data Spark Joy? Performance Gains From Domain Upsampling At The End Of Training'
authors: Cody Blakeney, Mansheej Paul, Brett W. Larsen, Sean Owen, Jonathan Frankle
conference: "Arxiv"
year: 2024
bibkey: blakeney2024does
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03476"}
tags: ['RAG', 'Training Techniques', 'Language Modeling', 'Pretraining Methods']
---
Pretraining datasets for large language models (LLMs) have grown to trillions
of tokens composed of large amounts of CommonCrawl (CC) web scrape along with
smaller, domain-specific datasets. It is expensive to understand the impact of
these domain-specific datasets on model capabilities as training at large FLOP
scales is required to reveal significant changes to difficult and emergent
benchmarks. Given the increasing cost of experimenting with pretraining data,
how does one determine the optimal balance between the diversity in general web
scrapes and the information density of domain specific data? In this work, we
show how to leverage the smaller domain specific datasets by upsampling them
relative to CC at the end of training to drive performance improvements on
difficult benchmarks. This simple technique allows us to improve up to 6.90 pp
on MMLU, 8.26 pp on GSM8K, and 6.17 pp on HumanEval relative to the base data
mix for a 7B model trained for 1 trillion (T) tokens, thus rivaling Llama-2
(7B)\\(\unicode\{x2014\}\\)a model trained for twice as long. We experiment with
ablating the duration of domain upsampling from 5% to 30% of training and find
that 10% to 20% percent is optimal for navigating the tradeoff between general
language modeling capabilities and targeted benchmarks. We also use domain
upsampling to characterize at scale the utility of individual datasets for
improving various benchmarks by removing them during this final phase of
training. This tool opens up the ability to experiment with the impact of
different pretraining datasets at scale, but at an order of magnitude lower
cost compared to full pretraining runs.
