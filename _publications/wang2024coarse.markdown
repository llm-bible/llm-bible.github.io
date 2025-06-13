---
layout: publication
title: 'Cof: Coarse To Fine-grained Image Understanding For Multi-modal Large Language Models'
authors: Yeyuan Wang, Dehong Gao, Bin Li, Rujiao Long, Lei Yi, Xiaoyan Cai, Libin Yang, Jinxia Zhang, Shanqing Yu, Qi Xuan
conference: "Arxiv"
year: 2024
bibkey: wang2024coarse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.16869"}
  - {name: "Code", url: "https://github.com/Gavin001201/CoF"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Has Code', 'Prompting', 'Attention Mechanism']
---
The impressive performance of Large Language Model (LLM) has prompted
researchers to develop Multi-modal LLM (MLLM), which has shown great potential
for various multi-modal tasks. However, current MLLM often struggles to
effectively address fine-grained multi-modal challenges. We argue that this
limitation is closely linked to the models' visual grounding capabilities. The
restricted spatial awareness and perceptual acuity of visual encoders
frequently lead to interference from irrelevant background information in
images, causing the models to overlook subtle but crucial details. As a result,
achieving fine-grained regional visual comprehension becomes difficult. In this
paper, we break down multi-modal understanding into two stages, from Coarse to
Fine (CoF). In the first stage, we prompt the MLLM to locate the approximate
area of the answer. In the second stage, we further enhance the model's focus
on relevant areas within the image through visual prompt engineering, adjusting
attention weights of pertinent regions. This, in turn, improves both visual
grounding and overall performance in downstream tasks. Our experiments show
that this approach significantly boosts the performance of baseline models,
demonstrating notable generalization and effectiveness. Our CoF approach is
available online at https://github.com/Gavin001201/CoF.
