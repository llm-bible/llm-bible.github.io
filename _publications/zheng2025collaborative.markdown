---
layout: publication
title: 'CITER: Collaborative Inference For Efficient Large Language Model Decoding With Token-level Routing'
authors: Wenhao Zheng, Yixiao Chen, Weitong Zhang, Souvik Kundu, Yun Li, Zhengzhong Liu, Eric P. Xing, Hongyi Wang, Huaxiu Yao
conference: "Arxiv"
year: 2025
bibkey: zheng2025collaborative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01976"}
  - {name: "Code", url: "https://github.com/aiming-lab/CITER"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Has Code', 'Applications']
---
Large language models have achieved remarkable success in various tasks but
suffer from high computational costs during inference, limiting their
deployment in resource-constrained applications. To address this issue, we
propose a novel Collaborative Inference with Token-lEvel Routing (CITER)
framework that enables efficient collaboration between small and large language
models (SLMs \& LLMs) through a token-level routing strategy. Specifically,
CITER routes non-critical tokens to an SLM for efficiency and routes critical
tokens to an LLM for generalization quality. We formulate router training as a
policy optimization, where the router receives rewards based on both the
quality of predictions and the inference costs of generation. This allows the
router to learn to predict token-level routing scores and make routing
decisions based on both the current token and the future impact of its
decisions. To further accelerate the reward evaluation process, we introduce a
shortcut which significantly reduces the costs of the reward estimation and
improving the practicality of our approach. Extensive experiments on five
benchmark datasets demonstrate that CITER reduces the inference costs while
preserving high-quality generation, offering a promising solution for real-time
and resource-constrained applications. Our data and code are available at
https://github.com/aiming-lab/CITER.
