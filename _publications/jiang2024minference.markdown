---
layout: publication
title: 'Minference 1.0: Accelerating Pre-filling For Long-context Llms Via Dynamic Sparse Attention'
authors: Huiqiang Jiang, Yucheng Li, Chengruidong Zhang, Qianhui Wu, Xufang Luo, Surin Ahn, Zhenhua Han, Amir H. Abdi, Dongsheng Li, Chin-yew Lin, Yuqing Yang, Lili Qiu
conference: "Arxiv"
year: 2024
bibkey: jiang2024minference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02490"}
  - {name: "Code", url: "https://aka.ms/MInference"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Prompting', 'Pre-Training', 'Attention Mechanism']
---
The computational challenges of Large Language Model (LLM) inference remain a
significant barrier to their widespread deployment, especially as prompt
lengths continue to increase. Due to the quadratic complexity of the attention
computation, it takes 30 minutes for an 8B LLM to process a prompt of 1M tokens
(i.e., the pre-filling stage) on a single A100 GPU. Existing methods for
speeding up prefilling often fail to maintain acceptable accuracy or efficiency
when applied to long-context LLMs. To address this gap, we introduce MInference
(Milliontokens Inference), a sparse calculation method designed to accelerate
pre-filling of long-sequence processing. Specifically, we identify three unique
patterns in long-context attention matrices-the A-shape, Vertical-Slash, and
Block-Sparsethat can be leveraged for efficient sparse computation on GPUs. We
determine the optimal pattern for each attention head offline and dynamically
build sparse indices based on the assigned pattern during inference. With the
pattern and sparse indices, we perform efficient sparse attention calculations
via our optimized GPU kernels to significantly reduce the latency in the
pre-filling stage of long-context LLMs. Our proposed technique can be directly
applied to existing LLMs without any modifications to the pre-training setup or
additional fine-tuning. By evaluating on a wide range of downstream tasks,
including InfiniteBench, RULER, PG-19, and Needle In A Haystack, and models
including LLaMA-3-1M, GLM4-1M, Yi-200K, Phi-3-128K, and Qwen2-128K, we
demonstrate that MInference effectively reduces inference latency by up to 10x
for pre-filling on an A100, while maintaining accuracy. Our code is available
at https://aka.ms/MInference.
