---
layout: publication
title: 'Hierarchical Balance Packing: Towards Efficient Supervised Fine-tuning For Long-context LLM'
authors: Yongqiang Yao, Jingru Tan, Kaihuan Liang, Feizhao Zhang, Yazhe Niu, Jiahao Hu, Ruihao Gong, Dahua Lin, Ningyi Xu
conference: "Arxiv"
year: 2025
bibkey: yao2025hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.07680"}
tags: ['Fine-Tuning', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Training Long-Context Large Language Models (LLMs) is challenging, as hybrid
training with long-context and short-context data often leads to workload
imbalances. Existing works mainly use data packing to alleviate this issue but
fail to consider imbalanced attention computation and wasted communication
overhead. This paper proposes Hierarchical Balance Packing (HBP), which designs
a novel batch-construction method and training recipe to address those
inefficiencies. In particular, the HBP constructs multi-level data packing
groups, each optimized with a distinct packing length. It assigns training
samples to their optimal groups and configures each group with the most
effective settings, including sequential parallelism degree and gradient
checkpointing configuration. To effectively utilize multi-level groups of data,
we design a dynamic training pipeline specifically tailored to HBP, including
curriculum learning, adaptive sequential parallelism, and stable loss. Our
extensive experiments demonstrate that our method significantly reduces
training time over multiple datasets and open-source models while maintaining
strong performance. For the largest DeepSeek-V2 (236B) MOE model, our method
speeds up the training by 2.4\\(\times\\) with competitive performance.
