---
layout: publication
title: 'Scalable Transformers For Neural Machine Translation'
authors: Peng Gao, Shijie Geng, Yu Qiao, Xiaogang Wang, Jifeng Dai, Hongsheng Li
conference: "Arxiv"
year: 2021
bibkey: gao2021scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.02242"}
tags: ['WMT', 'Training Techniques', 'Efficiency and Optimization', 'Model Architecture', 'Distillation', 'Pretraining Methods', 'Transformer', 'Applications']
---
Transformer has been widely adopted in Neural Machine Translation (NMT)
because of its large capacity and parallel training of sequence generation.
However, the deployment of Transformer is challenging because different
scenarios require models of different complexities and scales. Naively training
multiple Transformers is redundant in terms of both computation and memory. In
this paper, we propose a novel Scalable Transformers, which naturally contains
sub-Transformers of different scales and have shared parameters. Each
sub-Transformer can be easily obtained by cropping the parameters of the
largest Transformer. A three-stage training scheme is proposed to tackle the
difficulty of training the Scalable Transformers, which introduces additional
supervisions from word-level and sequence-level self-distillation. Extensive
experiments were conducted on WMT EN-De and En-Fr to validate our proposed
Scalable Transformers.
