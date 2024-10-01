---
layout: publication
title: 'Task-aware Specialization For Efficient And Robust Dense Retrieval For Open-domain Question Answering'
authors: Cheng Hao, Fang Hao, Liu Xiaodong, Gao Jianfeng
conference: "Arxiv"
year: 2022
bibkey: cheng2022task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.05156"}
  - {name: "Code", url: "https://github.com/microsoft/taser"}
tags: ['Applications', 'Has Code', 'Model Architecture', 'Reinforcement Learning']
---
Given its effectiveness on knowledge-intensive natural language processing tasks, dense retrieval models have become increasingly popular. Specifically, the de-facto architecture for open-domain question answering uses two isomorphic encoders that are initialized from the same pretrained model but separately parameterized for questions and passages. This bi-encoder architecture is parameter-inefficient in that there is no parameter sharing between encoders. Further, recent studies show that such dense retrievers underperform BM25 in various settings. We thus propose a new architecture, Task-aware Specialization for dense Retrieval (TASER), which enables parameter sharing by interleaving shared and specialized blocks in a single encoder. Our experiments on five question answering datasets show that TASER can achieve superior accuracy, surpassing BM25, while using about 60&#37; of the parameters as bi-encoder dense retrievers. In out-of-domain evaluations, TASER is also empirically more robust than bi-encoder dense retrievers. Our code is available at https://github.com/microsoft/taser.
