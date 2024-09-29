---
layout: publication
title: Cross-lingual Supervision Improves Large Language Models Pre-training
authors: Schioppa Andrea, Garcia Xavier, Firat Orhan
conference: "Arxiv"
year: 2023
bibkey: schioppa2023cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.11778"}
tags: ['Applications', 'In Context Learning', 'Language Modeling', 'Prompting', 'Tools', 'Training Techniques']
---
The recent rapid progress in pre-training Large Language Models has relied on using self-supervised language modeling objectives like next token prediction or span corruption. On the other hand Machine Translation Systems are mostly trained using cross-lingual supervision that requires aligned data between source and target languages. We demonstrate that pre-training Large Language Models on a mixture of a self-supervised Language Modeling objective and the supervised Machine Translation objective therefore including cross-lingual parallel data during pre-training yields models with better in-context learning abilities. As pre-training is a very resource-intensive process and a grid search on the best mixing ratio between the two objectives is prohibitively expensive we propose a simple yet effective strategy to learn it during pre-training.
