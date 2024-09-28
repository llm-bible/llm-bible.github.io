---
layout: publication
title: Finetuning Pretrained Transformers into RNNs
authors: Kasai Jungo, Peng Hao, Zhang Yizhe, Yogatama Dani, Ilharco Gabriel, Pappas Nikolaos, Mao Yi, Chen Weizhu, Smith Noah A.
conference: "Arxiv"
year: 2021
bibkey: kasai2021finetuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2103.13076"}
tags: ['ARXIV', 'Attention Mechanism', 'Training Techniques', 'Transformer']
---
Transformers have outperformed recurrent neural networks (RNNs) in natural language generation. But this comes with a significant computational cost as the attention mechanisms complexity scales quadratically with sequence length. Efficient transformer variants have received increasing interest in recent works. Among them a linear-complexity recurrent variant has proven well suited for autoregressive generation. It approximates the softmax attention with randomized or heuristic feature maps but can be difficult to train and may yield suboptimal accuracy. This work aims to convert a pretrained transformer into its efficient recurrent counterpart improving efficiency while maintaining accuracy. Specifically we propose a swap-then-finetune procedure in an off-the-shelf pretrained transformer we replace the softmax attention with its linear-complexity recurrent alternative and then finetune. With a learned feature map our approach provides an improved tradeoff between efficiency and accuracy over the standard transformer and other recurrent variants. We also show that the finetuning process has lower training cost relative to training these recurrent variants from scratch. As many models for natural language tasks are increasingly dependent on large-scale pretrained transformers this work presents a viable approach to improving inference efficiency without repeating the expensive pretraining process.
