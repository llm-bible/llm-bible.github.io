---
layout: publication
title: Lightningdot Pre45;training Visual45;semantic Embeddings For Real45;time Image45;text Retrieval
authors: Sun Siqi, Chen Yen-chun, Li Linjie, Wang Shuohang, Fang Yuwei, Liu Jingjing
conference: "Arxiv"
year: 2021
bibkey: sun2021pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2103.08784"}
  - {name: "Code", url: "https://github.com/intersun/LightningDOT"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Multimodal pre45;training has propelled great advancement in vision45;and45;language research. These large45;scale pre45;trained models although successful fatefully suffer from slow inference speed due to enormous computation cost mainly from cross45;modal attention in Transformer architecture. When applied to real45;life applications such latency and computation demand severely deter the practical use of pre45;trained models. In this paper we study Image45;text retrieval (ITR) the most mature scenario of V+L application which has been widely studied even prior to the emergence of recent pre45;trained models. We propose a simple yet highly effective approach LightningDOT that accelerates the inference time of ITR by thousands of times without sacrificing accuracy. LightningDOT removes the time45;consuming cross45;modal attention by pre45;training on three novel learning objectives extracting feature indexes offline and employing instant dot45;product matching with further re45;ranking which significantly speeds up retrieval process. In fact LightningDOT achieves new state of the art across multiple ITR benchmarks such as Flickr30k COCO and Multi30K outperforming existing pre45;trained models that consume 1000x magnitude of computational hours. Code and pre45;training checkpoints are available at https://github.com/intersun/LightningDOT.
