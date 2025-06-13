---
layout: publication
title: 'Clues Before Answers: Generation-enhanced Multiple-choice QA'
authors: Zixian Huang, Ao Wu, Jiaying Zhou, Yu Gu, Yue Zhao, Gong Cheng
conference: "Arxiv"
year: 2022
bibkey: huang2022clues
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.00274"}
tags: ['RAG', 'Applications', 'Tools', 'Reinforcement Learning']
---
A trending paradigm for multiple-choice question answering (MCQA) is using a
text-to-text framework. By unifying data in different tasks into a single
text-to-text format, it trains a generative encoder-decoder model which is both
powerful and universal. However, a side effect of twisting a generation target
to fit the classification nature of MCQA is the under-utilization of the
decoder and the knowledge that can be decoded. To exploit the generation
capability and underlying knowledge of a pre-trained encoder-decoder model, in
this paper, we propose a generation-enhanced MCQA model named GenMC. It
generates a clue from the question and then leverages the clue to enhance a
reader for MCQA. It outperforms text-to-text models on multiple MCQA datasets.
