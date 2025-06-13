---
layout: publication
title: 'Flashdecoding++: Faster Large Language Model Inference On Gpus'
authors: Ke Hong, Guohao Dai, Jiaming Xu, Qiuli Mao, Xiuhong Li, Jun Liu, Kangdi Chen, Yuhan Dong, Yu Wang
conference: "Arxiv"
year: 2023
bibkey: hong2023faster
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.01282"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Attention Mechanism']
---
As the Large Language Model (LLM) becomes increasingly important in various
domains. However, the following challenges still remain unsolved in
accelerating LLM inference: (1) Synchronized partial softmax update. The
softmax operation requires a synchronized update operation among each partial
softmax result, leading to ~20% overheads for the attention computation in
LLMs. (2) Under-utilized computation of flat GEMM. The shape of matrices
performing GEMM in LLM inference is flat, leading to under-utilized computation
and >50% performance loss after padding zeros in previous designs. (3)
Performance loss due to static dataflow. Kernel performance in LLM depends on
varied input data features, hardware configurations, etc. A single and static
dataflow may lead to a 50.25% performance loss for GEMMs of different shapes in
LLM inference.
  We present FlashDecoding++, a fast LLM inference engine supporting mainstream
LLMs and hardware back-ends. To tackle the above challenges, FlashDecoding++
creatively proposes: (1) Asynchronized softmax with unified max value.
FlashDecoding++ introduces a unified max value technique for different partial
softmax computations to avoid synchronization. (2) Flat GEMM optimization with
double buffering. FlashDecoding++ points out that flat GEMMs with different
shapes face varied bottlenecks. Then, techniques like double buffering are
introduced. (3) Heuristic dataflow with hardware resource adaptation.
FlashDecoding++ heuristically optimizes dataflow using different hardware
resource considering input dynamics. Due to the versatility of optimizations in
FlashDecoding++, FlashDecoding++ can achieve up to 4.86x and 2.18x speedup on
both NVIDIA and AMD GPUs compared to Hugging Face implementations.
FlashDecoding++ also achieves an average speedup of 1.37x compared to
state-of-the-art LLM inference engines on mainstream LLMs.
