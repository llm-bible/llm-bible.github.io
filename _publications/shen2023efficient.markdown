---
layout: publication
title: 'Efficient LLM Inference On Cpus'
authors: Haihao Shen, Hanwen Chang, Bo Dong, Yu Luo, Hengyu Meng
conference: "Arxiv"
year: 2023
bibkey: shen2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.00502"}
  - {name: "Code", url: "https://github.com/intel/intel-extension-for-transformers"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Quantization', 'Pretraining Methods', 'Transformer', 'Has Code']
---
Large language models (LLMs) have demonstrated remarkable performance and
tremendous potential across a wide range of tasks. However, deploying these
models has been challenging due to the astronomical amount of model parameters,
which requires a demand for large memory capacity and high memory bandwidth. In
this paper, we propose an effective approach that can make the deployment of
LLMs more efficiently. We support an automatic INT4 weight-only quantization
flow and design a special LLM runtime with highly-optimized kernels to
accelerate the LLM inference on CPUs. We demonstrate the general applicability
of our approach on popular LLMs including Llama2, Llama, GPT-NeoX, and showcase
the extreme inference efficiency on CPUs. The code is publicly available at:
https://github.com/intel/intel-extension-for-transformers.
