---
layout: publication
title: "Dialogconv: A Lightweight Fully Convolutional Network For Multi-view Response Selection"
authors: Liu Yongkang, Feng Shi, Gao Wei, Wang Daling, Zhang Yifei
conference: "Arxiv"
year: 2022
bibkey: liu2022lightweight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.13845"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
Current end-to-end retrieval-based dialogue systems are mainly based on Recurrent Neural Networks or Transformers with attention mechanisms. Although promising results have been achieved these models often suffer from slow inference or huge number of parameters. In this paper we propose a novel lightweight fully convolutional architecture called DialogConv for response selection. DialogConv is exclusively built on top of convolution to extract matching features of context and response. Dialogues are modeled in 3D views where DialogConv performs convolution operations on embedding view word view and utterance view to capture richer semantic information from multiple contextual views. On the four benchmark datasets compared with state-of-the-art baselines DialogConv is on average about 8.5x smaller in size and 79.39x and 10.64x faster on CPU and GPU devices respectively. At the same time DialogConv achieves the competitive effectiveness of response selection.
