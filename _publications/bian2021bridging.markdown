---
layout: publication
title: 'Bridging The Gap Between Language Model And Reading Comprehension: Unsupervised MRC Via Self-supervision'
authors: Bian Ning, Han Xianpei, Chen Bo, Lin Hongyu, He Ben, Sun Le
conference: "Arxiv"
year: 2021
bibkey: bian2021bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2107.08582"}
tags: ['Masked Language Model', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Despite recent success in machine reading comprehension (MRC), learning
high-quality MRC models still requires large-scale labeled training data, even
using strong pre-trained language models (PLMs). The pre-training tasks for
PLMs are not question-answering or MRC-based tasks, making existing PLMs unable
to be directly used for unsupervised MRC. Specifically, MRC aims to spot an
accurate answer span from the given document, but PLMs focus on token filling
in sentences. In this paper, we propose a new framework for unsupervised MRC.
Firstly, we propose to learn to spot answer spans in documents via
self-supervised learning, by designing a self-supervision pretext task for MRC
- Spotting-MLM. Solving this task requires capturing deep interactions between
sentences in documents. Secondly, we apply a simple sentence rewriting strategy
in the inference stage to alleviate the expression mismatch between questions
and documents. Experiments show that our method achieves a new state-of-the-art
performance for unsupervised MRC.
