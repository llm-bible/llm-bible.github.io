---
layout: publication
title: 'Lingualift: An Effective Two-stage Instruction Tuning Framework For Low-resource Language Reasoning'
authors: Hongbin Zhang, Kehai Chen, Xuefeng Bai, Yang Xiang, Min Zhang
conference: "Arxiv"
year: 2024
bibkey: zhang2024effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12499"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training']
---
Large language models (LLMs) have exhibited impressive multilingual reasoning
capabilities, driven by extensive multilingual pre-training corpora and
instruction fine-tuning data. However, a performance gap exists between high-
and low-resource language reasoning tasks due to the language imbalance in the
pre-training corpus, which is exacerbated by evaluation bias in existing
reasoning benchmarks lacking low-resource language coverage. To alleviate this
issue, we propose LinguaLIFT, a two-stage instruction tuning framework for
advancing low-resource language reasoning. LinguaLIFT employs a language
alignment layer to capture multilingual alignment in a code-switched tuning way
without requiring multilingual instruction or parallel data, thereby
transferring the cross-lingual reasoning capabilities to low-resource languages
through English-only instruction tuning data. To comprehensively evaluate the
multilingual reasoning capabilities, we introduce the Multilingual Math World
Problem (MMWP) benchmark, which spans 21 low-resource, 17 medium-resource, and
10 high-resource languages. Experimental results show that LinguaLIFT
outperforms several competitive baselines across MMWP and four widely used
benchmarks.
