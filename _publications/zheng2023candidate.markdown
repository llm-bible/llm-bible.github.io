---
layout: publication
title: Candidate Soups Fusing Candidate Results Improves Translation Quality for Non-Autoregressive Translation
authors: Zheng Huanran, Zhu Wei, Wang Pengfei, Wang Xiaoling
conference: "Arxiv"
year: 2023
bibkey: zheng2023candidate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.11503"}
tags: ['GPT', 'Pretraining Methods']
---
Non-autoregressive translation (NAT) model achieves a much faster inference speed than the autoregressive translation (AT) model because it can simultaneously predict all tokens during inference. However its translation quality suffers from degradation compared to AT. And existing NAT methods only focus on improving the NAT models performance but do not fully utilize it. In this paper we propose a simple but effective method called Candidate Soups which can obtain high-quality translations while maintaining the inference speed of NAT models. Unlike previous approaches that pick the individual result and discard the remainders Candidate Soups (CDS) can fully use the valuable information in the different candidate translations through model uncertainty. Extensive experiments on two benchmarks (WMT14 EN-DE and WMT16 EN-RO) demonstrate the effectiveness and generality of our proposed method which can significantly improve the translation quality of various base models. More notably our best variant outperforms the AT model on three translation tasks with 7.6 times speedup.
