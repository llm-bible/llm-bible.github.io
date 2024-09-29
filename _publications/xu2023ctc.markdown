---
layout: publication
title: Ctc-based Non-autoregressive Speech Translation
authors: Xu Chen, Liu Xiaoqian, Liu Xiaowen, Sun Qingxuan, Zhang Yuhao, Yang Murun, Dong Qianqian, Ko Tom, Wang Mingxuan, Xiao Tong, Ma Anxiang, Zhu Jingbo
conference: "Arxiv"
year: 2023
bibkey: xu2023ctc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.17358"}
tags: ['Attention Mechanism', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Combining end-to-end speech translation (ST) and non-autoregressive (NAR) generation is promising in language and speech processing for their advantages of less error propagation and low latency. In this paper we investigate the potential of connectionist temporal classification (CTC) for non-autoregressive speech translation (NAST). In particular we develop a model consisting of two encoders that are guided by CTC to predict the source and target texts respectively. Introducing CTC into NAST on both language sides has obvious challenges 1) the conditional independent generation somewhat breaks the interdependency among tokens and 2) the monotonic alignment assumption in standard CTC does not hold in translation tasks. In response we develop a prediction-aware encoding approach and a cross-layer attention approach to address these issues. We also use curriculum learning to improve convergence of training. Experiments on the MuST-C ST benchmarks show that our NAST model achieves an average BLEU score of 29.5 with a speed-up of 5.67× which is comparable to the autoregressive counterpart and even outperforms the previous best result of 0.9 BLEU points.
