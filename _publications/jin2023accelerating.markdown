---
layout: publication
title: 'Growlength: Accelerating Llms Pretraining By Progressively Growing Training Length'
authors: Hongye Jin, Xiaotian Han, Jingfeng Yang, Zhimeng Jiang, Chia-yuan Chang, Xia Hu
conference: "Arxiv"
year: 2023
bibkey: jin2023accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00576"}
tags: ['Pretraining Methods', 'Efficiency and Optimization', 'Training Techniques']
---
The evolving sophistication and intricacies of Large Language Models (LLMs)
yield unprecedented advancements, yet they simultaneously demand considerable
computational resources and incur significant costs. To alleviate these
challenges, this paper introduces a novel, simple, and effective method named
``\growlength'' to accelerate the pretraining process of LLMs. Our method
progressively increases the training length throughout the pretraining phase,
thereby mitigating computational costs and enhancing efficiency. For instance,
it begins with a sequence length of 128 and progressively extends to 4096. This
approach enables models to process a larger number of tokens within limited
time frames, potentially boosting their performance. In other words, the
efficiency gain is derived from training with shorter sequences optimizing the
utilization of resources. Our extensive experiments with various
state-of-the-art LLMs have revealed that models trained using our method not
only converge more swiftly but also exhibit superior performance metrics
compared to those trained with existing methods. Furthermore, our method for
LLMs pretraining acceleration does not require any additional engineering
efforts, making it a practical solution in the realm of LLMs.
