---
layout: publication
title: 'Moe-pruner: Pruning Mixture-of-experts Large Language Model Using The Hints From Its Router'
authors: Yanyue Xie, Zhi Zhang, Ding Zhou, Cong Xie, Ziang Song, Xin Liu, Yanzhi Wang, Xue Lin, An Xu
conference: "Arxiv"
year: 2024
bibkey: xie2024moe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12013"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Distillation', 'Pruning']
---
Mixture-of-Experts (MoE) architectures face challenges such as high memory
consumption and redundancy in experts. Pruning MoE can reduce network weights
while maintaining model performance. Motivated by the recent observation of
emergent large magnitude features in Large Language Models (LLM) and MoE
routing policy, we propose MoE-Pruner, a method that prunes weights with the
smallest magnitudes multiplied by the corresponding input activations and
router weights, on each output neuron. Our pruning method is one-shot,
requiring no retraining or weight updates. We evaluate our method on
Mixtral-8x7B and Mixtral-8x22B across multiple language benchmarks.
Experimental results show that our pruning method significantly outperforms
state-of-the-art LLM pruning methods. Furthermore, our pruned MoE models can
benefit from a pretrained teacher model through expert-wise knowledge
distillation, improving performance post-pruning. Experimental results
demonstrate that the Mixtral-8x7B model with 50% sparsity maintains 99% of the
performance of the original model after the expert-wise knowledge distillation.
