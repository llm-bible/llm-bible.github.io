---
layout: publication
title: Fine45;tuning By Curriculum Learning For Non45;autoregressive Neural Machine Translation
authors: Guo Junliang, Tan Xu, Xu Linli, Qin Tao, Chen Enhong, Liu Tie-yan
conference: "Arxiv"
year: 2019
bibkey: guo2019fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1911.08717"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Pretraining Methods', 'Training Techniques']
---
Non45;autoregressive translation (NAT) models remove the dependence on previous target tokens and generate all target tokens in parallel resulting in significant inference speedup but at the cost of inferior translation accuracy compared to autoregressive translation (AT) models. Considering that AT models have higher accuracy and are easier to train than NAT models and both of them share the same model configurations a natural idea to improve the accuracy of NAT models is to transfer a well45;trained AT model to an NAT model through fine45;tuning. However since AT and NAT models differ greatly in training strategy straightforward fine45;tuning does not work well. In this work we introduce curriculum learning into fine45;tuning for NAT. Specifically we design a curriculum in the fine45;tuning process to progressively switch the training from autoregressive generation to non45;autoregressive generation. Experiments on four benchmark translation datasets show that the proposed method achieves good improvement (more than 1 BLEU score) over previous NAT baselines in terms of translation accuracy and greatly speed up (more than 10 times) the inference process over AT baselines.
