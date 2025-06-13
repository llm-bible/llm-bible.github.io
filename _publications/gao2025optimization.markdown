---
layout: publication
title: 'Optimization-inspired Few-shot Adaptation For Large Language Models'
authors: Boyan Gao, Xin Wang, Yibo Yang, David Clifton
conference: "Arxiv"
year: 2025
bibkey: gao2025optimization
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.19107'}
tags: ['Few-Shot', 'Efficiency and Optimization', 'Applications', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) have demonstrated remarkable performance in real-world applications. However, adapting LLMs to novel tasks via fine-tuning often requires substantial training data and computational resources that are impractical in few-shot scenarios. Existing approaches, such as in-context learning and Parameter-Efficient Fine-Tuning (PEFT), face key limitations: in-context learning introduces additional inference computational overhead with limited performance gains, while PEFT models are prone to overfitting on the few demonstration examples. In this work, we reinterpret the forward pass of LLMs as an optimization process, a sequence of preconditioned gradient descent steps refining internal representations. Based on this connection, we propose Optimization-Inspired Few-Shot Adaptation (OFA), integrating a parameterization that learns preconditioners without introducing additional trainable parameters, and an objective that improves optimization efficiency by learning preconditioners based on a convergence bound, while simultaneously steering the optimization path toward the flat local minimum. Our method overcomes both issues of ICL-based and PEFT-based methods, and demonstrates superior performance over the existing methods on a variety of few-shot adaptation tasks in experiments.
