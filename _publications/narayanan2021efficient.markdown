---
layout: publication
title: Efficient Large-scale Language Model Training On GPU Clusters Using Megatron-lm
authors: Deepak Narayanan et al.
conference: Arxiv
year: 2021
citations: 238
bibkey: narayanan2021efficient
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.04473'}, {name: Code,
    url: 'https://github.com/nvidia/megatron-lm'}]
tags: [Training Techniques, Survey Paper]
---
Large language models have led to state-of-the-art accuracies across a range
of tasks. However, training these models efficiently is challenging for two
reasons: a) GPU memory capacity is limited, making it impossible to fit large
models on even a multi-GPU server, and b) the number of compute operations
required to train these models can result in unrealistically long training
times. Consequently, new methods of model parallelism such as tensor and
pipeline parallelism have been proposed. Unfortunately, naive usage of these
methods leads to fundamental scaling issues at thousands of GPUs, e.g., due to
expensive cross-node communication or devices spending significant time waiting
on other devices to make progress.
  In this paper, we show how different types of parallelism methods (tensor,
pipeline, and data parallelism) can be composed to scale to thousands of GPUs
and models with trillions of parameters. We survey techniques for pipeline
parallelism and propose a novel interleaved pipeline parallelism schedule that
can improve throughput by 10+% with memory footprint comparable to existing
approaches. We quantitatively study the trade-offs between tensor, pipeline,
and data parallelism, and provide intuition as to how to configure distributed
training of a large model. Our approach allows us to perform training
iterations on a model with 1 trillion parameters at 502 petaFLOP/s on 3072 GPUs
with achieved per-GPU throughput of 52% of theoretical peak. Our code is open
sourced at https://github.com/nvidia/megatron-lm.