---
layout: publication
title: 'Oberta: Improving Sparse Transfer Learning Via Improved Initialization, Distillation, And Pruning Regimes'
authors: Campos Daniel, Marques Alexandre, Kurtz Mark, Zhai Chengxiang
conference: "Arxiv"
year: 2023
bibkey: campos2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.17612"}
tags: ['Applications', 'BERT', 'Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Quantization', 'RAG', 'Training Techniques']
---
In this paper, we introduce the range of oBERTa language models, an easy-to-use set of language models which allows Natural Language Processing (NLP) practitioners to obtain between 3.8 and 24.3 times faster models without expertise in model compression. Specifically, oBERTa extends existing work on pruning, knowledge distillation, and quantization and leverages frozen embeddings improves distillation and model initialization to deliver higher accuracy on a broad range of transfer tasks. In generating oBERTa, we explore how the highly optimized RoBERTa differs from the BERT for pruning during pre-training and finetuning. We find it less amenable to compression during fine-tuning. We explore the use of oBERTa on seven representative NLP tasks and find that the improved compression techniques allow a pruned oBERTa model to match the performance of BERTbase and exceed the performance of Prune OFA Large on the SQUAD V1.1 Question Answering dataset, despite being 8x and 2x, respectively faster in inference. We release our code, training regimes, and associated model for broad usage to encourage usage and experimentation
