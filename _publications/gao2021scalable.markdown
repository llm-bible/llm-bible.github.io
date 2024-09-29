---
layout: publication
title: Scalable Transformers For Neural Machine Translation
authors: Gao Peng, Geng Shijie, Qiao Yu, Wang Xiaogang, Dai Jifeng, Li Hongsheng
conference: "Arxiv"
year: 2021
bibkey: gao2021scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.02242"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Transformer has been widely adopted in Neural Machine Translation (NMT) because of its large capacity and parallel training of sequence generation. However the deployment of Transformer is challenging because different scenarios require models of different complexities and scales. Naively training multiple Transformers is redundant in terms of both computation and memory. In this paper we propose a novel Scalable Transformers which naturally contains sub45;Transformers of different scales and have shared parameters. Each sub45;Transformer can be easily obtained by cropping the parameters of the largest Transformer. A three45;stage training scheme is proposed to tackle the difficulty of training the Scalable Transformers which introduces additional supervisions from word45;level and sequence45;level self45;distillation. Extensive experiments were conducted on WMT EN45;De and En45;Fr to validate our proposed Scalable Transformers.
