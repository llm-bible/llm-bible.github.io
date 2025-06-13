---
layout: publication
title: 'All-in-one Tuning And Structural Pruning For Domain-specific Llms'
authors: Lei Lu, Zhepeng Wang, Runxue Bao, Mengbing Wang, Fangyi Li, Yawen Wu, Weiwen Jiang, Jie Xu, Yanzhi Wang, Shangqian Gao
conference: "Arxiv"
year: 2024
bibkey: lu2024all
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.14426'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Pruning', 'Pretraining Methods']
---
Existing pruning techniques for large language models (LLMs) targeting
domain-specific applications typically follow a two-stage process: pruning the
pretrained general-purpose LLMs and then fine-tuning the pruned LLMs on
specific domains. However, the pruning decisions, derived from the pretrained
weights, remain unchanged during fine-tuning, even if the weights have been
updated. Therefore, such a combination of the pruning decisions and the
finetuned weights may be suboptimal, leading to non-negligible performance
degradation. To address these limitations, we propose ATP: All-in-One Tuning
and Structural Pruning, a unified one-stage structural pruning and fine-tuning
approach that dynamically identifies the current optimal substructure
throughout the fine-tuning phase via a trainable pruning decision generator.
Moreover, given the limited available data for domain-specific applications,
Low-Rank Adaptation (LoRA) becomes a common technique to fine-tune the LLMs. In
ATP, we introduce LoRA-aware forward and sparsity regularization to ensure that
the substructures corresponding to the learned pruning decisions can be
directly removed after the ATP process. ATP outperforms the state-of-the-art
two-stage pruning methods on tasks in the legal and healthcare domains. More
specifically, ATP recovers up to 88% and 91% performance of the dense model
when pruning 40% parameters of LLaMA2-7B and LLaMA3-8B models, respectively.
