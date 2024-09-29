---
layout: publication
title: Redcoast\: A Lightweight Tool To Automate Distributed Training Of Llms On Any Gpu/tpus
authors: Tan Bowen, Zhu Yun, Liu Lijuan, Wang Hongyi, Zhuang Yonghao, Chen Jindong, Xing Eric, Hu Zhiting
conference: "Arxiv"
year: 2023
bibkey: tan2023lightweight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.16355"}
tags: ['Agentic', 'Fine Tuning', 'GPT', 'Language Modeling', 'Large Scale Training', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
The recent progress of AI can be largely attributed to large language models (LLMs). However their escalating memory requirements introduce challenges for machine learning (ML) researchers and engineers. Addressing this requires developers to partition a large model to distribute it across multiple GPUs or TPUs. This necessitates considerable coding and intricate configuration efforts with existing model parallel tools such as Megatron-LM DeepSpeed and Alpa. These tools require users expertise in machine learning systems (MLSys) creating a bottleneck in LLM development particularly for developers without MLSys background. In this work we present RedCoast (Redco) a lightweight and user-friendly tool crafted to automate distributed training and inference for LLMs as well as to simplify ML pipeline development. The design of Redco emphasizes two key aspects. Firstly to automate model parallelism our study identifies two straightforward rules to generate tensor parallel strategies for any given LLM. Integrating these rules into Redco facilitates effortless distributed LLM training and inference eliminating the need of additional coding or complex configurations. We demonstrate the effectiveness by applying Redco on a set of LLM architectures such as GPT-J LLaMA T5 and OPT up to the size of 66B. Secondly we propose a mechanism that allows for the customization of diverse ML pipelines through the definition of merely three functions avoiding redundant and formulaic code like multi-host related processing. This mechanism proves adaptable across a spectrum of ML algorithms from foundational language modeling to complex algorithms like meta-learning and reinforcement learning. As a result Redco implementations exhibit significantly fewer lines of code compared to their official counterparts.
