---
layout: publication
title: 'Refinecoder: Iterative Improving Of Large Language Models Via Adaptive Critique Refinement For Code Generation'
authors: Changzhi Zhou, Xinyu Zhang, Dandan Song, Xiancai Chen, Wanli Gu, Huipeng Ma, Yuhang Tian, Mengdi Zhang, Linmei Hu
conference: "Arxiv"
year: 2025
bibkey: zhou2025iterative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.09183"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Distillation']
---
Code generation has attracted increasing attention with the rise of Large
Language Models (LLMs). Many studies have developed powerful code LLMs by
synthesizing code-related instruction data and applying supervised fine-tuning.
However, these methods are limited by teacher model distillation and ignore the
potential of iterative refinement by self-generated code. In this paper, we
propose Adaptive Critique Refinement (ACR), which enables the model to refine
itself by self-generated code and external critique, rather than directly
imitating the code responses of the teacher model. Concretely, ACR includes a
composite scoring system with LLM-as-a-Judge to evaluate the quality of code
responses and a selective critique strategy with LLM-as-a-Critic to critique
self-generated low-quality code responses. We develop the RefineCoder series by
iteratively applying ACR, achieving continuous performance improvement on
multiple code generation benchmarks. Compared to the baselines of the same
size, our proposed RefineCoder series can achieve comparable or even superior
performance using less data.
