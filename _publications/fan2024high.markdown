---
layout: publication
title: 'HLAT: High-quality Large Language Model Pre-trained On AWS Trainium'
authors: Haozheng Fan, Hao Zhou, Guangtai Huang, Parameswaran Raman, Xinwei Fu, Gaurav Gupta, Dhananjay Ram, Yida Wang, Jun Huan
conference: "Arxiv"
year: 2024
bibkey: fan2024high
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10630"}
  - {name: "Code", url: "https://github.com/awslabs/HLAT)"}
tags: ['Training Techniques', 'Tools', 'RAG', 'Large-Scale Training', 'Has Code', 'Pre-Training', 'Applications']
---
Getting large language models (LLMs) to perform well on the downstream tasks
requires pre-training over trillions of tokens. This typically demands a large
number of powerful computational devices in addition to a stable distributed
training framework to accelerate the training. The growing number of
applications leveraging AI/ML led to a scarcity of the expensive conventional
accelerators (such as GPUs), which emphasizes the need for the alternative
specialized-accelerators that are scalable and cost-efficient. AWS Trainium is
the second-generation machine learning accelerator purposely built for training
large deep learning models. However, training LLMs with billions of parameters
on AWS Trainium is challenging due to its relatively nascent software
ecosystem. In this paper, we showcase HLAT: a family of 7B and 70B decoder-only
LLMs pre-trained using 4096 AWS Trainium accelerators over 1.8 trillion tokens.
The performance of HLAT is benchmarked against popular open source models
including LLaMA and OpenLLaMA, which have been trained on NVIDIA GPUs and
Google TPUs, respectively. On various evaluation tasks, we show that HLAT
achieves model quality on par with the baselines of similar model size. We also
open-source all the training scripts and configurations of HLAT
(https://github.com/awslabs/HLAT) and share the best practice of using the
NeuronX Distributed Training (NxDT), a customized distributed training library
for AWS Trainium. Our work demonstrates that AWS Trainium powered by NxDT is
able to successfully pre-train state-of-the-art LLM models with high
performance and cost-effectiveness.
