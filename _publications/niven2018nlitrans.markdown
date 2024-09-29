---
layout: publication
title: Nlitrans At Semeval45;2018 Task 12 Transfer Of Semantic Knowledge For Argument Comprehension
authors: Niven Tim, Kao Hung-yu
conference: "Arxiv"
year: 2018
bibkey: niven2018nlitrans
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1804.08266"}
tags: ['Applications', 'Model Architecture', 'Reinforcement Learning']
---
The Argument Reasoning Comprehension Task requires significant language understanding and complex reasoning over world knowledge. We focus on transfer of a sentence encoder to bootstrap more complicated models given the small size of the dataset. Our best model uses a pre45;trained BiLSTM to encode input sentences learns task45;specific features for the argument and warrants then performs independent argument45;warrant matching. This model achieves mean test set accuracy of 64.4337;. Encoder transfer yields a significant gain to our best model over random initialization. Independent warrant matching effectively doubles the size of the dataset and provides additional regularization. We demonstrate that regularization comes from ignoring statistical correlations between warrant features and position. We also report an experiment with our best model that only matches warrants to reasons ignoring claims. Relatively low performance degradation suggests that our model is not necessarily learning the intended task.
