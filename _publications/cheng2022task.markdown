---
layout: publication
title: Task45;aware Specialization For Efficient And Robust Dense Retrieval For Open45;domain Question Answering
authors: Cheng Hao, Fang Hao, Liu Xiaodong, Gao Jianfeng
conference: "Arxiv"
year: 2022
bibkey: cheng2022task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.05156"}
  - {name: "Code", url: "https://github.com/microsoft/taser"}
tags: ['Applications', 'Has Code', 'Model Architecture', 'Reinforcement Learning']
---
Given its effectiveness on knowledge45;intensive natural language processing tasks dense retrieval models have become increasingly popular. Specifically the de45;facto architecture for open45;domain question answering uses two isomorphic encoders that are initialized from the same pretrained model but separately parameterized for questions and passages. This bi45;encoder architecture is parameter45;inefficient in that there is no parameter sharing between encoders. Further recent studies show that such dense retrievers underperform BM25 in various settings. We thus propose a new architecture Task45;aware Specialization for dense Retrieval (TASER) which enables parameter sharing by interleaving shared and specialized blocks in a single encoder. Our experiments on five question answering datasets show that TASER can achieve superior accuracy surpassing BM25 while using about 6037; of the parameters as bi45;encoder dense retrievers. In out45;of45;domain evaluations TASER is also empirically more robust than bi45;encoder dense retrievers. Our code is available at https://github.com/microsoft/taser.
