---
layout: publication
title: Slimfit Memory45;efficient Fine45;tuning Of Transformer45;based Models Using Training Dynamics
authors: Ardakani Arash, Haan Altan, Tan Shangyin, Popovici Doru Thom, Cheung Alvin, Iancu Costin, Sen Koushik
conference: "Arxiv"
year: 2023
bibkey: ardakani2023memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.18513"}
tags: ['BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Quantization', 'RAG', 'Training Techniques', 'Transformer']
---
Transformer45;based models such as BERT and ViT have achieved state45;of45;the45;art results across different natural language processing (NLP) and computer vision (CV) tasks. However these models are extremely memory intensive during their fine45;tuning process making them difficult to deploy on GPUs with limited memory resources. To address this issue we introduce a new tool called SlimFit that reduces the memory requirements of these models by dynamically analyzing their training dynamics and freezing less45;contributory layers during fine45;tuning. The layers to freeze are chosen using a runtime inter45;layer scheduling algorithm. SlimFit adopts quantization and pruning for particular layers to balance the load of dynamic activations and to minimize the memory footprint of static activations where static activations refer to those that cannot be discarded regardless of freezing. This allows SlimFit to freeze up to 9537; of layers and reduce the overall on45;device GPU memory usage of transformer45;based models such as ViT and BERT by an average of 2.2x across different NLP and CV benchmarks/datasets such as GLUE SQuAD 2.0 CIFAR45;10 CIFAR45;100 and ImageNet with an average degradation of 0.237; in accuracy. For such NLP and CV tasks SlimFit can reduce up to 3.1x the total on45;device memory usage with an accuracy degradation of only up to 0.437;. As a result while fine45;tuning of ViT on ImageNet and BERT on SQuAD 2.0 with a batch size of 128 requires 3 and 2 32GB GPUs respectively SlimFit enables their fine45;tuning on a single 32GB GPU without any significant accuracy degradation.
