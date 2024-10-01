---
layout: publication
title: 'Slimfit: Memory-efficient Fine-tuning Of Transformer-based Models Using Training Dynamics'
authors: Ardakani Arash, Haan Altan, Tan Shangyin, Popovici Doru Thom, Cheung Alvin, Iancu Costin, Sen Koushik
conference: "Arxiv"
year: 2023
bibkey: ardakani2023memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.18513"}
tags: ['BERT', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Quantization', 'RAG', 'Training Techniques', 'Transformer']
---
Transformer-based models, such as BERT and ViT, have achieved state-of-the-art results across different natural language processing (NLP) and computer vision (CV) tasks. However, these models are extremely memory intensive during their fine-tuning process, making them difficult to deploy on GPUs with limited memory resources. To address this issue, we introduce a new tool called SlimFit that reduces the memory requirements of these models by dynamically analyzing their training dynamics and freezing less-contributory layers during fine-tuning. The layers to freeze are chosen using a runtime inter-layer scheduling algorithm. SlimFit adopts quantization and pruning for particular layers to balance the load of dynamic activations and to minimize the memory footprint of static activations, where static activations refer to those that cannot be discarded regardless of freezing. This allows SlimFit to freeze up to 95&#37; of layers and reduce the overall on-device GPU memory usage of transformer-based models such as ViT and BERT by an average of 2.2x, across different NLP and CV benchmarks/datasets such as GLUE, SQuAD 2.0, CIFAR-10, CIFAR-100 and ImageNet with an average degradation of 0.2&#37; in accuracy. For such NLP and CV tasks, SlimFit can reduce up to 3.1x the total on-device memory usage with an accuracy degradation of only up to 0.4&#37;. As a result, while fine-tuning of ViT on ImageNet and BERT on SQuAD 2.0 with a batch size of 128 requires 3 and 2 32GB GPUs respectively, SlimFit enables their fine-tuning on a single 32GB GPU without any significant accuracy degradation.
