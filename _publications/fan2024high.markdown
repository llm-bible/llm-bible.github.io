---
layout: publication
title: HLAT High45;quality Large Language Model Pre45;trained On AWS Trainium
authors: Fan Haozheng, Zhou Hao, Huang Guangtai, Raman Parameswaran, Fu Xinwei, Gupta Gaurav, Ram Dhananjay, Wang Yida, Huan Jun
conference: "Arxiv"
year: 2024
bibkey: fan2024high
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10630"}
tags: ['Applications', 'Large Scale Training', 'RAG', 'Tools', 'Training Techniques']
---
Getting large language models (LLMs) to perform well on the downstream tasks requires pre45;training over trillions of tokens. This typically demands a large number of powerful computational devices in addition to a stable distributed training framework to accelerate the training. The growing number of applications leveraging AI/ML had led to a scarcity of the expensive conventional accelerators (such as GPUs) which begs the need for the alternative specialized45;accelerators that are scalable and cost45;efficient. AWS Trainium is the second45;generation machine learning accelerator that has been purposely built for training large deep learning models. Its corresponding instance Amazon EC2 trn1 is an alternative to GPU instances for LLM training. However training LLMs with billions of parameters on trn1 is challenging due to its relatively nascent software ecosystem. In this paper we showcase HLAT a 7 billion parameter decoder45;only LLM pre45;trained using trn1 instances over 1.8 trillion tokens. The performance of HLAT is benchmarked against popular open source baseline models including LLaMA and OpenLLaMA which have been trained on NVIDIA GPUs and Google TPUs respectively. On various evaluation tasks we show that HLAT achieves model quality on par with the baselines. We also share the best practice of using the Neuron Distributed Training Library (NDTL) a customized distributed training library for AWS Trainium to achieve efficient training. Our work demonstrates that AWS Trainium powered by the NDTL is able to successfully pre45;train state45;of45;the45;art LLM models with high performance and cost45;effectiveness.
