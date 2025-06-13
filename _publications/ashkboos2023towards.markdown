---
layout: publication
title: 'QUIK: Towards End-to-end 4-bit Inference On Generative Large Language Models'
authors: Saleh Ashkboos, Ilia Markov, Elias Frantar, Tingxuan Zhong, Xincheng Wang, Jie Ren, Torsten Hoefler, Dan Alistarh
conference: "Arxiv"
year: 2023
bibkey: ashkboos2023towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.09259'}
  - {name: "Code", url: 'https://github.com/IST-DASLab/QUIK'}
tags: ['Has Code', 'Efficiency and Optimization', 'GPT', 'Model Architecture', 'Quantization', 'Prompting']
---
Large Language Models (LLMs) from the GPT family have become extremely
popular, leading to a race towards reducing their inference costs to allow for
efficient local computation. Yet, the vast majority of existing work focuses on
weight-only quantization, which can reduce runtime costs in the memory-bound
one-token-at-a-time generative setting, but does not address them in
compute-bound scenarios, such as batched inference or prompt processing. In
this paper, we address the general quantization problem, where both weights and
activations should be quantized. We show, for the first time, that the majority
of inference computations for large generative models such as LLaMA, OPT, and
Falcon can be performed with both weights and activations being cast to 4 bits,
in a way that leads to practical speedups, while at the same time maintaining
good accuracy. We achieve this via a hybrid quantization strategy called QUIK,
which compresses most of the weights and activations to 4-bit, while keeping
some outlier weights and activations in higher-precision. The key feature of
our scheme is that it is designed with computational efficiency in mind: we
provide GPU kernels matching the QUIK format with highly-efficient layer-wise
runtimes, which lead to practical end-to-end throughput improvements of up to
3.4x relative to FP16 execution. We provide detailed studies for models from
the OPT, LLaMA-2 and Falcon families, as well as a first instance of accurate
inference using quantization plus 2:4 sparsity. Code is available at:
https://github.com/IST-DASLab/QUIK.
