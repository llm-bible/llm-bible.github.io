---
layout: publication
title: "Compensate Quantization Errors: Make Weights Hierarchical To Compensate Each Other"
authors: Gao Yifei, Ou Jie, Wang Lei, Xiao Yuting, Xiang Zhiyuan, Dai Ruiting, Cheng Jun
conference: "Arxiv"
year: 2024
bibkey: gao2024compensate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16299"}
tags: ['Efficiency And Optimization', 'Quantization', 'RAG', 'Training Techniques']
---
Emergent Large Language Models (LLMs) use their extraordinary performance and powerful deduction capacity to discern from traditional language models. However the expenses of computational resources and storage for these LLMs are stunning quantization then arises as a trending conversation. To address accuracy decay caused by quantization two streams of works in post-training quantization methods stand out. One uses other weights to compensate existing quantization error while the other transfers the quantization difficulty to other parts in the model. Combining both merits we introduce Learnable Singular value Increment (LSI) as an advanced solution. LSI uses Singular Value Decomposition to extract singular values of the weights and make them learnable to help weights compensate each other conditioned on activation. Incorporating LSI with existing techniques we achieve state-of-the-art performance in diverse quantization settings no matter in weight-only weight-activation or extremely low bit scenarios. By unleashing the potential of LSI efficient finetuning on quantized model is no longer a prohibitive problem.
