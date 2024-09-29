---
layout: publication
title: ERNIE-GEN An Enhanced Multi-Flow Pre-training and Fine-tuning Framework for Natural Language Generation
authors: Xiao Dongling, Zhang Han, Li Yukun, Sun Yu, Tian Hao, Wu Hua, Wang Haifeng
conference: "Arxiv"
year: 2020
bibkey: xiao2020ernie
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2001.11314"}
tags: ['Applications', 'Attention Mechanism', 'Ethics And Bias', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Current pre-training works in natural language generation pay little attention to the problem of exposure bias on downstream tasks. To address this issue we propose an enhanced multi-flow sequence to sequence pre-training and fine-tuning framework named ERNIE-GEN which bridges the discrepancy between training and inference with an infilling generation mechanism and a noise-aware generation method. To make generation closer to human writing patterns this framework introduces a span-by-span generation flow that trains the model to predict semantically-complete spans consecutively rather than predicting word by word. Unlike existing pre-training methods ERNIE-GEN incorporates multi-granularity target sampling to construct pre-training data which enhances the correlation between encoder and decoder. Experimental results demonstrate that ERNIE-GEN achieves state-of-the-art results with a much smaller amount of pre-training data and parameters on a range of language generation tasks including abstractive summarization (Gigaword and CNN/DailyMail) question generation (SQuAD) dialogue generation (Persona-Chat) and generative question answering (CoQA).
