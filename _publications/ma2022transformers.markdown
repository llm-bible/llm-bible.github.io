---
layout: publication
title: 'Torchscale: Transformers At Scale'
authors: Shuming Ma, Hongyu Wang, Shaohan Huang, Wenhui Wang, Zewen Chi, Li Dong, Alon Benhaim, Barun Patra, Vishrav Chaudhary, Xia Song, Furu Wei
conference: "Arxiv"
year: 2022
bibkey: ma2022transformers
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.13184"}
tags: ['Transformer', 'Tools', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Language Modeling', 'Large-Scale Training', 'Training Techniques', 'Pretraining Methods']
---
Large Transformers have achieved state-of-the-art performance across many
tasks. Most open-source libraries on scaling Transformers focus on improving
training or inference with better parallelization. In this work, we present
TorchScale, an open-source toolkit that allows researchers and developers to
scale up Transformers efficiently and effectively. TorchScale has the
implementation of several modeling techniques, which can improve modeling
generality and capability, as well as training stability and efficiency.
Experimental results on language modeling and neural machine translation
demonstrate that TorchScale can successfully scale Transformers to different
sizes without tears. The library is available at https://aka.ms/torchscale.
