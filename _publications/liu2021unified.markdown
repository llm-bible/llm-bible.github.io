---
layout: publication
title: Unified Multimodal Pre45;training And Prompt45;based Tuning For Vision45;language Understanding And Generation
authors: Liu Tianyi, Wu Zuxuan, Xiong Wenhan, Chen Jingjing, Jiang Yu-gang
conference: "Arxiv"
year: 2021
bibkey: liu2021unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.05587"}
tags: ['Applications', 'BERT', 'GPT', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
Most existing vision45;language pre45;training methods focus on understanding tasks and use BERT45;like objectives (masked language modeling and image45;text matching) during pretraining. Although they perform well in many understanding downstream tasks e.g. visual question answering image45;text retrieval and visual entailment they do not possess the ability to generate. To tackle this problem we propose Unified multimodal pre45;training for both Vision45;Language understanding and generation (UniVL). The proposed UniVL is capable of handling both understanding tasks and generative tasks. We augment existing pretraining paradigms that only use random masks with causal masks i.e. triangular masks that mask out future tokens such that the pre45;trained models can have autoregressive generation abilities by design. We formulate several previous understanding tasks as a text generation task and propose to use prompt45;based method for fine45;tuning on different downstream tasks. Our experiments show that there is a trade45;off between understanding tasks and generation tasks while using the same model and a feasible way to improve both tasks is to use more data. Our UniVL framework attains comparable performance to recent vision45;language pre45;training methods on both understanding tasks and generation tasks. Moreover we demostrate that prompt45;based finetuning is more data45;efficient 45; it outperforms discriminative methods in few45;shot scenarios.
