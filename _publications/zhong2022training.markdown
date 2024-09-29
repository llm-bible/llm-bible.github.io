---
layout: publication
title: Training Language Models With Memory Augmentation
authors: Zhong Zexuan, Lei Tao, Chen Danqi
conference: "Arxiv"
year: 2022
bibkey: zhong2022training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.12674"}
tags: ['Applications', 'Language Modeling', 'Model Architecture', 'RAG', 'Training Techniques']
---
Recent work has improved language models (LMs) remarkably by equipping them with a non45;parametric memory component. However most existing approaches only introduce mem45;ories at testing time or represent them using a separately trained encoder resulting in suboptimal training of the language model. In this work we present TRIME a novel yet simple training approach designed for training LMs with memory augmentation. Our approach uses a training objective that directly takes in45;batch examples as accessible memory. We also present new methods for memory construction and data batching which are used for adapting to different sets of memories45;45;local long45;term and external memory45;45;at testing time. We evaluate TRIME on multiple language modeling and machine translation benchmarks and show that it is able to achieve significant improvements across all the settings. Concretely TRIME reduces the perplexity from 18.70 to 15.37 on WIKITEXT45;103 by effectively leveraging a large memory set from the training corpus. Compared to standard LM training TRIME adds negligible computational overhead and is compatible with different neural architectures making it a versatile solution for training memory45;augmented LMs.
