---
layout: publication
title: 'Task Scheduling For Efficient Inference Of Large Language Models On Single Moderate GPU Systems'
authors: Wenxiang Lin, Xinglin Pan, Shaohuai Shi, Xuan Wang, Xiaowen Chu
conference: "Arxiv"
year: 2024
bibkey: lin2024task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.15715"}
tags: ['Efficiency and Optimization', 'Pruning', 'Quantization', 'Prompting', 'Applications']
---
Large language models~(LLMs) are known for their high demand on computing
resources and memory due to their substantial model size, which leads to
inefficient inference on moderate GPU systems. Techniques like quantization or
pruning can shrink model sizes but often impair accuracy, making them
unsuitable for practical applications. In this work, we introduce \modelname\{\},
a high-performance inference engine designed to speed up LLM inference without
compromising model accuracy. \modelname\{\} incorporates three innovative methods
to increase inference efficiency: 1) model partitioning to allow asynchronous
processing of tasks across CPU computation, GPU computation, and CPU-GPU
communication, 2) an adaptive partition algorithm to optimize the use of CPU,
GPU, and PCIe communication capabilities, and 3) a token assignment strategy to
handle diverse prompt and generation tasks during LLM inference. Comprehensive
experiments were conducted with various LLMs such as Mixtral, LLaMA-2, Qwen,
and PhiMoE across three test environments featuring different CPUs and GPUs.
The experimental findings demonstrate that \modelname\{\} achieves speeds between
\\(1.11\times\\) to \\(1.80\times\\) faster in decoding and \\(1.69\times\\) to
\\(6.33\times\\) faster in pre-filling, leading to an overall speedup ranging from
\\(1.25\times\\) to \\(2.04\times\\) compared to state-of-the-art solutions, llama.cpp
and Fiddler.
