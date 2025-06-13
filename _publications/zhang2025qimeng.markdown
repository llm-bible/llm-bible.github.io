---
layout: publication
title: 'Qimeng-tensorop: Automatically Generating High-performance Tensor Operators With Hardware Primitives'
authors: Xuzhi Zhang, Shaohui Peng, Qirui Zhou, Yuanbo Wen, Qi Guo, Ruizhi Chen, Xinguo Zhu, Weiqiang Xiong, Haixin Chen, Congying Ma, Ke Gao, Chen Zhao, Yanjun Wu, Yunji Chen, Ling Li
conference: "Arxiv"
year: 2025
bibkey: zhang2025qimeng
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.06302'}
tags: ['Prompting', 'Tools', 'Model Architecture']
---
Computation-intensive tensor operators constitute over 90% of the computations in Large Language Models (LLMs) and Deep Neural Networks.Automatically and efficiently generating high-performance tensor operators with hardware primitives is crucial for diverse and ever-evolving hardware architectures like RISC-V, ARM, and GPUs, as manually optimized implementation takes at least months and lacks portability.LLMs excel at generating high-level language codes, but they struggle to fully comprehend hardware characteristics and produce high-performance tensor operators. We introduce a tensor-operator auto-generation framework with a one-line user prompt (QiMeng-TensorOp), which enables LLMs to automatically exploit hardware characteristics to generate tensor operators with hardware primitives, and tune parameters for optimal performance across diverse hardware. Experimental results on various hardware platforms, SOTA LLMs, and typical tensor operators demonstrate that QiMeng-TensorOp effectively unleashes the computing capability of various hardware platforms, and automatically generates tensor operators of superior performance. Compared with vanilla LLMs, QiMeng-TensorOp achieves up to \\(1291 \times\\) performance improvement. Even compared with human experts, QiMeng-TensorOp could reach \\(251 %\\) of OpenBLAS on RISC-V CPUs, and \\(124 %\\) of cuBLAS on NVIDIA GPUs. Additionally, QiMeng-TensorOp also significantly reduces development costs by \\(200 \times\\) compared with human experts.
