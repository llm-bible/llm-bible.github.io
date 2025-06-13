---
layout: publication
title: 'Adaptive Computation Pruning For The Forgetting Transformer'
authors: Zhixuan Lin, Johan Obando-ceron, Xu Owen He, Aaron Courville
conference: "Arxiv"
year: 2025
bibkey: lin2025adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.06949"}
  - {name: "Code", url: "https://github.com/zhixuan-lin/arctic-fox"}
tags: ['Transformer', 'Efficiency and Optimization', 'Pruning', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
The recently proposed Forgetting Transformer (FoX) incorporates a forget gate
into softmax attention and has shown consistently better or on-par performance
compared to the standard RoPE-based Transformer. Notably, many attention heads
in FoX tend to forget quickly, causing their output at each timestep to rely
primarily on the local context. Based on this observation, we propose Adaptive
Computation Pruning (ACP) for FoX, a method that dynamically prunes
computations involving input-output dependencies that are strongly decayed by
the forget gate. This is achieved using a dynamically set pruning threshold
that ensures that the pruned attention weights remain negligible. We apply ACP
to language model pretraining with FoX and show it consistently reduces the
number of FLOPs in softmax attention by around 70% across different model sizes
and context lengths, resulting in a roughly 10% to 35% improvement in training
throughput. Furthermore, longer context lengths yield greater computational
savings. All these speed improvements are achieved without any performance
degradation. We also perform several analyses to provide deeper insights into
our method, such as examining the pruning patterns and analyzing the
distribution of FLOP savings across different attention heads. Our code is
available at https://github.com/zhixuan-lin/arctic-fox.
