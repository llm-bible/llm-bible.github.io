---
layout: publication
title: Bridging The Gap Between Language Model And Reading Comprehension Unsupervised MRC Via Self45;supervision
authors: Bian Ning, Han Xianpei, Chen Bo, Lin Hongyu, He Ben, Sun Le
conference: "Arxiv"
year: 2021
bibkey: bian2021bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2107.08582"}
tags: ['Masked Language Model', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Despite recent success in machine reading comprehension (MRC) learning high45;quality MRC models still requires large45;scale labeled training data even using strong pre45;trained language models (PLMs). The pre45;training tasks for PLMs are not question45;answering or MRC45;based tasks making existing PLMs unable to be directly used for unsupervised MRC. Specifically MRC aims to spot an accurate answer span from the given document but PLMs focus on token filling in sentences. In this paper we propose a new framework for unsupervised MRC. Firstly we propose to learn to spot answer spans in documents via self45;supervised learning by designing a self45;supervision pretext task for MRC 45; Spotting45;MLM. Solving this task requires capturing deep interactions between sentences in documents. Secondly we apply a simple sentence rewriting strategy in the inference stage to alleviate the expression mismatch between questions and documents. Experiments show that our method achieves a new state45;of45;the45;art performance for unsupervised MRC.
