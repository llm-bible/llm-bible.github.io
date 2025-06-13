---
layout: publication
title: 'Lightrouter: Towards Efficient LLM Collaboration With Minimal Overhead'
authors: Yifan Zhang, Xinkui Zhao, Zuxin Wang, Guanjie Cheng, Yueshen Xu, Shuiguang Deng, Jianwei Yin
conference: "Arxiv"
year: 2025
bibkey: zhang2025towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16221'}
tags: ['RAG', 'Efficiency and Optimization', 'Tools']
---
The rapid advancement of large language models has unlocked remarkable capabilities across a diverse array of natural language processing tasks. However, the considerable differences among available LLMs-in terms of cost, performance, and computational demands-pose significant challenges for users aiming to identify the most suitable model for specific tasks. In this work, we present LightRouter, a novel framework designed to systematically select and integrate a small subset of LLMs from a larger pool, with the objective of jointly optimizing both task performance and cost efficiency. LightRouter leverages an adaptive selection mechanism to identify models that require only a minimal number of boot tokens, thereby reducing costs, and further employs an effective integration strategy to combine their outputs. Extensive experiments across multiple benchmarks demonstrate that LightRouter matches or outperforms widely-used ensemble baselines, achieving up to a 25% improvement in accuracy. Compared with leading high-performing models, LightRouter achieves comparable performance while reducing inference costs by up to 27%. Importantly, our framework operates without any prior knowledge of individual models and relies exclusively on inexpensive, lightweight models. This work introduces a practical approach for efficient LLM selection and provides valuable insights into optimal strategies for model combination.
