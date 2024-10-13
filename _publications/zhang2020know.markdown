---
layout: publication
title: 'Know What You Don''t Need: Single-shot Meta-pruning For Attention Heads'
authors: Zhang Zhengyan, Qi Fanchao, Liu Zhiyuan, Liu Qun, Sun Maosong
conference: "Arxiv"
year: 2020
bibkey: zhang2020know
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2011.03770"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Quantization', 'Training Techniques', 'Transformer']
---
Deep pre-trained Transformer models have achieved state-of-the-art results
over a variety of natural language processing (NLP) tasks. By learning rich
language knowledge with millions of parameters, these models are usually
overparameterized and significantly increase the computational overhead in
applications. It is intuitive to address this issue by model compression. In
this work, we propose a method, called Single-Shot Meta-Pruning, to compress
deep pre-trained Transformers before fine-tuning. Specifically, we focus on
pruning unnecessary attention heads adaptively for different downstream tasks.
To measure the informativeness of attention heads, we train our Single-Shot
Meta-Pruner (SMP) with a meta-learning paradigm aiming to maintain the
distribution of text representations after pruning. Compared with existing
compression methods for pre-trained models, our method can reduce the overhead
of both fine-tuning and inference. Experimental results show that our pruner
can selectively prune 50% of attention heads with little impact on the
performance on downstream tasks and even provide better text representations.
The source code will be released in the future.
