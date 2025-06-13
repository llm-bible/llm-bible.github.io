---
layout: publication
title: 'Fastattention: Extend Flashattention2 To Npus And Low-resource Gpus'
authors: Haoran Lin, Xianzhi Yu, Kang Zhao, Lu Hou, Zongyuan Zhan, Stanislav Kamenev, Han Bao, Ting Hu, Mingkai Wang, Qixin Chang, Siyue Sui, Weihao Sun, Jiaxin Hu, Jun Yao, Zekun Yin, Cheng Qian, Ying Zhang, Yinfei Pan, Yu Yang, Weiguo Liu
conference: "Arxiv"
year: 2024
bibkey: lin2024extend
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16663"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
FlashAttention series has been widely applied in the inference of large
language models (LLMs). However, FlashAttention series only supports the
high-level GPU architectures, e.g., Ampere and Hopper. At present,
FlashAttention series is not easily transferrable to NPUs and low-resource
GPUs. Moreover, FlashAttention series is inefficient for multi- NPUs or GPUs
inference scenarios. In this work, we propose FastAttention which pioneers the
adaptation of FlashAttention series for NPUs and low-resource GPUs to boost LLM
inference efficiency. Specifically, we take Ascend NPUs and Volta-based GPUs as
representatives for designing our FastAttention. We migrate FlashAttention
series to Ascend NPUs by proposing a novel two-level tiling strategy for
runtime speedup, tiling-mask strategy for memory saving and the
tiling-AllReduce strategy for reducing communication overhead, respectively.
Besides, we adapt FlashAttention for Volta-based GPUs by redesigning the
operands layout in shared memory and introducing a simple yet effective CPU-GPU
cooperative strategy for efficient memory utilization. On Ascend NPUs, our
FastAttention can achieve a 10.7\\(\times\\) speedup compared to the standard
attention implementation. Llama-7B within FastAttention reaches up to
5.16\\(\times\\) higher throughput than within the standard attention. On Volta
architecture GPUs, FastAttention yields 1.43\\(\times\\) speedup compared to its
equivalents in \texttt\{xformers\}. Pangu-38B within FastAttention brings
1.46\\(\times\\) end-to-end speedup using FasterTransformer. Coupled with the
propose CPU-GPU cooperative strategy, FastAttention supports a maximal input
length of 256K on 8 V100 GPUs. All the codes will be made available soon.
