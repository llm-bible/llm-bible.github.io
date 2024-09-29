---
layout: publication
title: Residual Tree Aggregation of Layers for Neural Machine Translation
authors: Li Guoliang, Li Yiyang
conference: "Arxiv"
year: 2021
bibkey: li2021residual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2107.14590"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Although attention-based Neural Machine Translation has achieved remarkable progress in recent layers it still suffers from issue of making insufficient use of the output of each layer. In transformer it only uses the top layer of encoder and decoder in the subsequent process which makes it impossible to take advantage of the useful information in other layers. To address this issue we propose a residual tree aggregation of layers for Transformer(RTAL) which helps to fuse information across layers. Specifically we try to fuse the information across layers by constructing a post-order binary tree. In additional to the last node we add the residual connection to the process of generating child nodes. Our model is based on the Neural Machine Translation model Transformer and we conduct our experiments on WMT14 English-to-German and WMT17 English-to-France translation tasks. Experimental results across language pairs show that the proposed approach outperforms the strong baseline model significantly
