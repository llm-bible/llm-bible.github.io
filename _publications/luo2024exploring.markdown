---
layout: publication
title: '\(\gamma-\)mod: Exploring Mixture-of-depth Adaptation For Multimodal Large Language Models'
authors: Yaxin Luo, Gen Luo, Jiayi Ji, Yiyi Zhou, Xiaoshuai Sun, Zhiqiang Shen, Rongrong Ji
conference: "Arxiv"
year: 2024
bibkey: luo2024exploring
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.13859'}
tags: ['Attention Mechanism', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
Despite the significant progress in multimodal large language models (MLLMs),
their high computational cost remains a barrier to real-world deployment.
Inspired by the mixture of depths (MoDs) in natural language processing, we aim
to address this limitation from the perspective of ``activated tokens''. Our
key insight is that if most tokens are redundant for the layer computation,
then can be skipped directly via the MoD layer. However, directly converting
the dense layers of MLLMs to MoD layers leads to substantial performance
degradation. To address this issue, we propose an innovative MoD adaptation
strategy for existing MLLMs called \\(\gamma\\)-MoD. In \\(\gamma\\)-MoD, a novel
metric is proposed to guide the deployment of MoDs in the MLLM, namely rank of
attention maps (ARank). Through ARank, we can effectively identify which layer
is redundant and should be replaced with the MoD layer. Based on ARank, we
further propose two novel designs to maximize the computational sparsity of
MLLM while maintaining its performance, namely shared vision-language router
and masked routing learning. With these designs, more than 90% dense layers of
the MLLM can be effectively converted to the MoD ones. To validate our method,
we apply it to three popular MLLMs, and conduct extensive experiments on 9
benchmark datasets. Experimental results not only validate the significant
efficiency benefit of \\(\gamma\\)-MoD to existing MLLMs but also confirm its
generalization ability on various MLLMs. For example, with a minor performance
drop, i.e., -1.5%, \\(\gamma\\)-MoD can reduce the training and inference time of
LLaVA-HR by 31.0% and 53.2%, respectively.
