---
layout: publication
title: 'EAGLE-3: Scaling Up Inference Acceleration Of Large Language Models Via Training-time Test'
authors: Yuhui Li, Fangyun Wei, Chao Zhang, Hongyang Zhang
conference: "Arxiv"
year: 2025
bibkey: li2025eagle
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.01840'}
  - {name: "Code", url: 'https://github.com/SafeAILab/EAGLE'}
tags: ['Has Code', 'Tools', 'Training Techniques', 'Merging']
---
The sequential nature of modern LLMs makes them expensive and slow, and
speculative sampling has proven to be an effective solution to this problem.
Methods like EAGLE perform autoregression at the feature level, reusing
top-layer features from the target model to achieve better results than vanilla
speculative sampling. A growing trend in the LLM community is scaling up
training data to improve model intelligence without increasing inference costs.
However, we observe that scaling up data provides limited improvements for
EAGLE. We identify that this limitation arises from EAGLE's feature prediction
constraints. In this paper, we introduce EAGLE-3, which abandons feature
prediction in favor of direct token prediction and replaces reliance on
top-layer features with multi-layer feature fusion via a technique named
training-time test. These improvements significantly enhance performance and
enable the draft model to fully benefit from scaling up training data. Our
experiments include both chat models and reasoning models, evaluated on five
tasks. The results show that EAGLE-3 achieves a speedup ratio up to 6.5x, with
about 1.4x improvement over EAGLE-2. In the SGLang framework, EAGLE-3 achieves
a 1.38x throughput improvement at a batch size of 64. The code is available at
https://github.com/SafeAILab/EAGLE.
