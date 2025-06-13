---
layout: publication
title: 'Mlissard: Multilingual Long And Simple Sequential Reasoning Benchmarks'
authors: Mirelle Bueno, Roberto Lotufo, Rodrigo Nogueira
conference: "Arxiv"
year: 2024
bibkey: bueno2024multilingual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.06396'}
  - {name: "Code", url: 'https://github.com/unicamp-dl/Lissard'}
tags: ['Has Code', 'Training Techniques']
---
Language models are now capable of solving tasks that require dealing with
long sequences consisting of hundreds of thousands of tokens. However, they
often fail on tasks that require repetitive use of simple rules, even on
sequences that are much shorter than those seen during training. For example,
state-of-the-art LLMs can find common items in two lists with up to 20 items
but fail when lists have 80 items. In this paper, we introduce MLissard, a
multilingual benchmark designed to evaluate models' abilities to process and
generate texts of varied lengths and offers a mechanism for controlling
sequence complexity.
  Our evaluation of open-source and proprietary models show a consistent
decline in performance across all models and languages as the complexity of the
sequence increases. Surprisingly, the use of in-context examples in languages
other than English helps increase extrapolation performance significantly. The
datasets and code are available at https://github.com/unicamp-dl/Lissard
