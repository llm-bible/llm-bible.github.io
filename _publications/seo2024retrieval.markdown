---
layout: publication
title: 'Retrieval-augmented Data Augmentation For Low-resource Domain Tasks'
authors: Minju Seo, Jinheon Baek, James Thorne, Sung Ju Hwang
conference: "Arxiv"
year: 2024
bibkey: seo2024retrieval
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.13482'}
tags: ['RAG', 'Prompting', 'Training Techniques', 'Tools']
---
Despite large successes of recent language models on diverse tasks, they
suffer from severe performance degeneration in low-resource settings with
limited training data available. Many existing works tackle this problem by
generating synthetic data from the training data and then training models on
them, recently using Large Language Models (LLMs). However, in low-resource
settings, the amount of seed data samples to use for data augmentation is very
small, which makes generated samples suboptimal and less diverse. To tackle
this challenge, we propose a novel method that augments training data by
incorporating a wealth of examples from other datasets, along with the given
training data. Specifically, we first retrieve the relevant instances from
other datasets, such as their input-output pairs or contexts, based on their
similarities with the given seed data, and then prompt LLMs to generate new
samples with the contextual information within and across the original and
retrieved samples. This approach can ensure that the generated data is not only
relevant but also more diverse than what could be achieved using the limited
seed data alone. We validate our proposed Retrieval-Augmented Data Augmentation
(RADA) framework on multiple datasets under low-resource settings of training
and test-time data augmentation scenarios, on which it outperforms existing
LLM-powered data augmentation baselines.
