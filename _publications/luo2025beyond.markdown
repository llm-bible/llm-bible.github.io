---
layout: publication
title: 'Beyond Decoder-only: Large Language Models Can Be Good Encoders For Machine Translation'
authors: Yingfeng Luo, Tong Zheng, Yongyu Mu, Bei Li, Qinghong Zhang, Yongqi Gao, Ziqiang Xu, Peinan Feng, Xiaoqian Liu, Tong Xiao, Jingbo Zhu
conference: "Arxiv"
year: 2025
bibkey: luo2025beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.06594"}
tags: ['WMT', 'Model Architecture', 'Efficiency and Optimization', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Applications', 'Attention Mechanism']
---
The field of neural machine translation (NMT) has changed with the advent of large language models (LLMs). Much of the recent emphasis in natural language processing (NLP) has been on modeling machine translation and many other problems using a single pre-trained Transformer decoder, while encoder-decoder architectures, which were the standard in earlier NMT models, have received relatively less attention. In this paper, we explore translation models that are universal, efficient, and easy to optimize, by marrying the world of LLMs with the world of NMT. We apply LLMs to NMT encoding and leave the NMT decoder unchanged. We also develop methods for adapting LLMs to work better with the NMT decoder. Furthermore, we construct a new dataset involving multiple tasks to assess how well the machine translation system generalizes across various tasks. Evaluations on the WMT and our datasets show that results using our method match or surpass a range of baselines in terms of translation quality, but achieve \\(2.4 \sim 6.5 \times\\) inference speedups and a \\(75%\\) reduction in the memory footprint of the KV cache. It also demonstrates strong generalization across a variety of translation-related tasks.
