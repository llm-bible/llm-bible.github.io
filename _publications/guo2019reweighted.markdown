---
layout: publication
title: "Reweighted Proximal Pruning For Large-scale Language Representation"
authors: Guo Fu-ming, Liu Sijia, Mungall Finlay S., Lin Xue, Wang Yanzhi
conference: "Arxiv"
year: 2019
bibkey: guo2019reweighted
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.12486"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Tools', 'Training Techniques']
---
Recently pre-trained language representation flourishes as the mainstay of the natural language understanding community e.g. BERT. These pre-trained language representations can create state-of-the-art results on a wide range of downstream tasks. Along with continuous significant performance improvement the size and complexity of these pre-trained neural models continue to increase rapidly. Is it possible to compress these large-scale language representation models How will the pruned language representation affect the downstream multi-task transfer learning objectives In this paper we propose Reweighted Proximal Pruning (RPP) a new pruning method specifically designed for a large-scale language representation model. Through experiments on SQuAD and the GLUE benchmark suite we show that proximal pruned BERT keeps high accuracy for both the pre-training task and the downstream multiple fine-tuning tasks at high prune ratio. RPP provides a new perspective to help us analyze what large-scale language representation might learn. Additionally RPP makes it possible to deploy a large state-of-the-art language representation model such as BERT on a series of distinct devices (e.g. online servers mobile phones and edge devices).
