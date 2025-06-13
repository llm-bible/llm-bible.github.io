---
layout: publication
title: 'Ttt4rec: A Test-time Training Approach For Rapid Adaption In Sequential Recommendation'
authors: Zhaoqi Yang, Yanan Wang, Yong Ge
conference: "Arxiv"
year: 2024
bibkey: yang2024test
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.19142"}
  - {name: "Code", url: "https://github.com/ZhaoqiZachYang/TTT4Rec"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Has Code']
---
Sequential recommendation tasks, which aim to predict the next item a user
will interact with, typically rely on models trained solely on historical data.
However, in real-world scenarios, user behavior can fluctuate in the long
interaction sequences, and training data may be limited to model this dynamics.
To address this, Test-Time Training (TTT) offers a novel approach by using
self-supervised learning during inference to dynamically update model
parameters. This allows the model to adapt to new user interactions in
real-time, leading to more accurate recommendations. In this paper, we propose
TTT4Rec, a sequential recommendation framework that integrates TTT to better
capture dynamic user behavior. By continuously updating model parameters during
inference, TTT4Rec is particularly effective in scenarios where user
interaction sequences are long, training data is limited, or user behavior is
highly variable. We evaluate TTT4Rec on three widely-used recommendation
datasets, demonstrating that it achieves performance on par with or exceeding
state-of-the-art models. The codes are available at
https://github.com/ZhaoqiZachYang/TTT4Rec.
