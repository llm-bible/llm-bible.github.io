---
layout: publication
title: 'Online Speculative Decoding'
authors: Xiaoxuan Liu, Lanxiang Hu, Peter Bailis, Alvin Cheung, Zhijie Deng, Ion Stoica, Hao Zhang
conference: "Arxiv"
year: 2023
bibkey: liu2023online
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.07177'}
  - {name: "Code", url: 'https://github.com/LiuXiaoxuanPKU/OSD'}
tags: ['Has Code', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Reinforcement Learning']
---
Speculative decoding is a pivotal technique to accelerate the inference of
large language models (LLMs) by employing a smaller draft model to predict the
target model's outputs. However, its efficacy can be limited due to the low
predictive accuracy of the draft model, particularly when faced with diverse
text inputs and a significant capability gap between the draft and target
models. We introduce online speculative decoding to address this challenge. The
main idea is to continuously update the (multiple) draft model(s) on observed
user query data. Adapting to query distribution mitigates the shifts between
the training distribution of the draft model and the query distribution,
enabling the draft model to more accurately predict the target model's outputs.
We develop a prototype of online speculative decoding based on knowledge
distillation and evaluate it using both synthetic and real query data. The
results show a substantial increase in the token acceptance rate by 0.1 to
0.65, bringing 1.42x to 2.17x latency reduction. Our code is available at
https://github.com/LiuXiaoxuanPKU/OSD.
