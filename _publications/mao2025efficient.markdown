---
layout: publication
title: 'Unimod: Efficient Unified Multimodal Transformers With Mixture-of-depths'
authors: Weijia Mao, Zhenheng Yang, Mike Zheng Shou
conference: "Arxiv"
year: 2025
bibkey: mao2025efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.06474'}
  - {name: "Code", url: 'https://github.com/showlab/UniMoD'}
tags: ['Attention Mechanism', 'Has Code', 'Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pruning', 'Multimodal Models', 'Pretraining Methods']
---
Unified multimodal transformers, which handle both generation and
understanding tasks within a shared parameter space, have received increasing
attention in recent research. Although various unified transformers have been
proposed, training these models is costly due to redundant tokens and heavy
attention computation. In the past, studies on large language models have
demonstrated that token pruning methods, such as Mixture of Depths (MoD), can
significantly improve computational efficiency. MoD employs a router to select
the most important ones for processing within a transformer layer. However,
directly applying MoD-based token pruning to unified transformers will result
in suboptimal performance because different tasks exhibit varying levels of
token redundancy. In our work, we analyze the unified transformers by (1)
examining attention weight patterns, (2) evaluating the layer importance and
token redundancy, and (3) analyzing task interactions. Our findings reveal that
token redundancy is primarily influenced by different tasks and layers.
Building on these findings, we introduce UniMoD, a task-aware token pruning
method that employs a separate router for each task to determine which tokens
should be pruned. We apply our method to Show-o and Emu3, reducing training
FLOPs by approximately 15% in Show-o and 40% in Emu3, while maintaining or
improving performance on several benchmarks. Code will be released at
https://github.com/showlab/UniMoD.
