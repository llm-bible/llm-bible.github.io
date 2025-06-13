---
layout: publication
title: 'Packmamba: Efficient Processing Of Variable-length Sequences In Mamba Training'
authors: Haoran Xu, Ziqian Liu, Rong Fu, Zhongling Su, Zerui Wang, Zheng Cai, Zhilin Pei, Xingcheng Zhang
conference: "Arxiv"
year: 2024
bibkey: xu2024efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.03865'}
tags: ['Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Merging', 'Pretraining Methods']
---
With the evolution of large language models, traditional Transformer models
become computationally demanding for lengthy sequences due to the quadratic
growth in computation with respect to the sequence length. Mamba, emerging as a
groundbreaking architecture in the field of generative AI, demonstrates
remarkable proficiency in handling elongated sequences with reduced
computational and memory complexity. Nevertheless, the existing training
framework of Mamba presents inefficiency with variable-length sequence inputs.
Either single-sequence training results in low GPU utilization, or batched
processing of variable-length sequences to a maximum length incurs considerable
memory and computational overhead. To address this problem, we analyze the
performance of bottleneck operators in Mamba under diverse tensor shapes and
proposed PackMamba, a high-throughput Mamba that efficiently handles
variable-length sequences. Diving deep into state-space models (SSMs), we
modify the parallel operators to avoid passing information between individual
sequences while maintaining high performance. Experimental results on an NVIDIA
A100 GPU demonstrate throughput exceeding the baseline single-sequence
processing scheme: 3.06x speedup on the 1.4B model and 2.62x on the 2.8B model.
