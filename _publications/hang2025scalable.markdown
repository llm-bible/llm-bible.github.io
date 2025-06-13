---
layout: publication
title: 'Scalable Complexity Control Facilitates Reasoning Ability Of Llms'
authors: Liangkai Hang, Junjie Yao, Zhiwei Bai, Tianyi Chen, Yang Chen, Rongjie Diao, Hezhou Li, Pengxiao Lin, Zhiwei Wang, Cheng Xu, Zhongwang Zhang, Zhangchen Zhou, Zhiyu Li, Zehao Lin, Kai Chen, Feiyu Xiong, Yaoyu Zhang, Weinan E, Hongkang Yang, Zhi-qin John Xu
conference: "Arxiv"
year: 2025
bibkey: hang2025scalable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23013'}
tags: ['Tools']
---
The reasoning ability of large language models (LLMs) has been rapidly advancing in recent years, attracting interest in more fundamental approaches that can reliably enhance their generalizability. This work demonstrates that model complexity control, conveniently implementable by adjusting the initialization rate and weight decay coefficient, improves the scaling law of LLMs consistently over varying model sizes and data sizes. This gain is further illustrated by comparing the benchmark performance of 2.4B models pretrained on 1T tokens with different complexity hyperparameters. Instead of fixing the initialization std, we found that a constant initialization rate (the exponent of std) enables the scaling law to descend faster in both model and data sizes. These results indicate that complexity control is a promising direction for the continual advancement of LLMs.
