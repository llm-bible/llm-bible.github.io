---
layout: publication
title: "Unified Multimodal Pre-training And Prompt-based Tuning For Vision-language Understanding And Generation"
authors: Liu Tianyi, Wu Zuxuan, Xiong Wenhan, Chen Jingjing, Jiang Yu-gang
conference: "Arxiv"
year: 2021
bibkey: liu2021unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.05587"}
tags: ['Applications', 'BERT', 'Few Shot', 'Fine Tuning', 'GPT', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
Most existing vision-language pre-training methods focus on understanding tasks and use BERT-like objectives (masked language modeling and image-text matching) during pretraining. Although they perform well in many understanding downstream tasks e.g. visual question answering image-text retrieval and visual entailment they do not possess the ability to generate. To tackle this problem we propose Unified multimodal pre-training for both Vision-Language understanding and generation (UniVL). The proposed UniVL is capable of handling both understanding tasks and generative tasks. We augment existing pretraining paradigms that only use random masks with causal masks i.e. triangular masks that mask out future tokens such that the pre-trained models can have autoregressive generation abilities by design. We formulate several previous understanding tasks as a text generation task and propose to use prompt-based method for fine-tuning on different downstream tasks. Our experiments show that there is a trade-off between understanding tasks and generation tasks while using the same model and a feasible way to improve both tasks is to use more data. Our UniVL framework attains comparable performance to recent vision-language pre-training methods on both understanding tasks and generation tasks. Moreover we demostrate that prompt-based finetuning is more data-efficient - it outperforms discriminative methods in few-shot scenarios.
