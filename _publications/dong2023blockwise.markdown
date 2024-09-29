---
layout: publication
title: Blockwise Compression Of Transformer45;based Models Without Retraining
authors: Dong Gaochen, Chen Wei
conference: "Arxiv"
year: 2023
bibkey: dong2023blockwise
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.01483"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Tools', 'Training Techniques', 'Transformer']
---
Transformer45;based models exemplified by GPT45;3 ChatGPT and GPT45;4 have recently garnered considerable attention in both academia and industry due to their promising performance in general language tasks. Nevertheless these models typically involve computationally encoding processes and in some cases decoding processes as well both of which are fundamentally large45;scale matrix multiplication. These operations bring the inevitable challenges of massive computation resources and huge memory footprint usually requiring at least 10^23 FLOPs and hundreds of gigabytes respectively. A common method to address this issue is to reduce the computational and memory requirements by applying layerwise quantization to the transformer replacing the usual fp32 data type with a low45;bit equivalent. Unfortunately this method often leads to decreased model accuracy and necessitates time45;consuming retraining. Such retraining not only requires fine45;tuning skills but also substantial computational resources posing challenges for users. To specifically tackle these issues we propose BCT a framework of blockwise compression for transformers without retraining aiming to facilitate model deployment. Unlike layerwise compression methods BCT achieves finer compression of the entire transformer by operating blockwise. This method mitigates data distribution deviation caused by quantization eliminating the requirement for retraining. BCT effectively compresses all components of the model including but not limited to the embedding matrix multiplication GELU Softmax layer normalization and intermediate results. In a case study an efficient model is compressed by BCT achieving up to 7.988x compression. Subsequently we also evaluate it on several General Language Understanding Evaluation (GLUE) datasets.
