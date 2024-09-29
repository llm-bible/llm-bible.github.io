---
layout: publication
title: Corda Context-oriented Decomposition Adaptation Of Large Language Models
authors: Yang Yibo, Li Xiaojie, Zhou Zhongzhu, Song Shuaiwen Leon, Wu Jianlong, Nie Liqiang, Ghanem Bernard
conference: "Arxiv"
year: 2024
bibkey: yang2024context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05223"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Current parameter-efficient fine-tuning (PEFT) methods build adapters without considering the context of downstream task to learn or the context of important knowledge to maintain. As a result there is often a performance gap compared to full-parameter finetuning and meanwhile the finetuned model suffers from catastrophic forgetting of the pre-trained world knowledge. In this paper we propose CorDA a Context-oriented Decomposition Adaptation method that builds learnable adapters from weight decomposition oriented by the context of downstream task or world knowledge. Concretely we collect a few data samples and perform singular value decomposition for each linear layer of a pre-trained LLM multiplied by the covariance matrix of the input activation using these samples. By doing so the context of the representative samples is captured through deciding the factorizing orientation. Our method enables two options the knowledge-preserved adaptation and the instruction-previewed adaptation. For the former we use question-answering samples to obtain the covariance matrices and use the decomposed components with the smallest r singular values to initialize a learnable adapter with the others frozen such that the world knowledge is better preserved. For the latter we use the instruction data from the finetuning task such as math or coding to orientate the decomposition and train the largest r components that capture the main characteristics of the task to learn. We conduct extensive experiments on Math Code and Instruction Following tasks. Our knowledge-preserved adaptation not only achieves better performance than LoRA on finetuning tasks but also mitigates the forgetting of world knowledge. Our instruction-previewed adaptation is able to further enhance the finetuning performance surpassing full-parameter finetuning and the state-of-the-art PEFT methods.
