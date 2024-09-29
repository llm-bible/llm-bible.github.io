---
layout: publication
title: Pruning Large Language Models With Semi-structural Adaptive Sparse Training
authors: Huang Weiyu, Hu Yuezhou, Jian Guohao, Zhu Jun, Chen Jianfei
conference: "Arxiv"
year: 2024
bibkey: huang2024pruning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.20584"}
tags: ['Distillation', 'Efficiency And Optimization', 'Pretraining Methods', 'Pruning', 'Quantization', 'Training Techniques']
---
The tremendous success of Large Language Models (LLMs) across various complex tasks relies heavily on their substantial scale which raises challenges during model deployment due to their large memory consumption. Recently numerous studies have attempted to compress LLMs using one-shot pruning methods. However these methods often experience considerable performance degradation on complex language understanding tasks calling into question the feasibility of pruning in LLMs. To address this issue we propose a pruning pipeline for semi-structured sparse models via retraining termed Adaptive Sparse Trainer (AST). Unlike previous one-shot pruning methods AST incrementally transforms dense models into sparse ones by applying decay to masked weights while allowing the model to adaptively select masks throughout the training process. Furthermore we observe that using distillation with a dense model as the teacher can prevent the sparse model from falling into local optima and accelerate convergence. In addition we incorporate extra well-initialized parameters to further enhance model performance with minimal increase in memory footprint. AST can significantly enhance model performance approaching the level of dense models. When applied to the LLaMA2-7B model AST reduces the zero-shot accuracy gap between dense and semi-structured sparse models to 1.1237; across multiple zero-shot tasks utilizing less than 0.437; of the pretraining tokens. Our work demonstrates the feasibility of deploying semi-structured sparse large language models and introduces a novel method for achieving highly compressed models when combined with existing quantization techniques.
