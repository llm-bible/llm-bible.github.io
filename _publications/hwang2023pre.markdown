---
layout: publication
title: Pre45;gated Moe An Algorithm45;system Co45;design For Fast And Scalable Mixture45;of45;expert Inference
authors: Hwang Ranggi, Wei Jianyu, Cao Shijie, Hwang Changho, Tang Xiaohu, Cao Ting, Yang Mao
conference: "Arxiv"
year: 2023
bibkey: hwang2023pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.12066"}
tags: ['Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Large language models (LLMs) based on transformers have made significant strides in recent years the success of which is driven by scaling up their model size. Despite their high algorithmic performance the computational and memory requirements of LLMs present unprecedented challenges. To tackle the high compute requirements of LLMs the Mixture45;of45;Experts (MoE) architecture was introduced which is able to scale its model size without proportionally scaling up its computational requirements. Unfortunately MoEs high memory demands and dynamic activation of sparse experts restrict its applicability to real45;world problems. Previous solutions that offload MoEs memory45;hungry expert parameters to CPU memory fall short because the latency to migrate activated experts from CPU to GPU incurs high performance overhead. Our proposed Pre45;gated MoE system effectively tackles the compute and memory challenges of conventional MoE architectures using our algorithm45;system co45;design. Pre45;gated MoE employs our novel pre45;gating function which alleviates the dynamic nature of sparse expert activation allowing our proposed system to address the large memory footprint of MoEs while also achieving high performance. We demonstrate that Pre45;gated MoE is able to improve performance reduce GPU memory consumption while also maintaining the same level of model quality. These features allow our Pre45;gated MoE system to cost45;effectively deploy large45;scale LLMs using just a single GPU with high performance.
