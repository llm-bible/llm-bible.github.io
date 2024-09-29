---
layout: publication
title: Nomad45;attention Efficient LLM Inference On Cpus Through Multiply45;add45;free Attention
authors: Zhang Tianyi, Yi Jonah Wonkyu, Yao Bowen, Xu Zhaozhuo, Shrivastava Anshumali
conference: "Arxiv"
year: 2024
bibkey: zhang2024nomad
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.01273"}
  - {name: "Code", url: "https://github.com/tonyzhang617/nomad&#45;dist"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG']
---
Large language model inference on Central Processing Units (CPU) is challenging due to the vast quantities of expensive Multiply45;Add (MAD) matrix operations in the attention computations. In this paper we argue that there is a rare gem in modern CPUs Single45;Instruction45;Multiple45;Data (SIMD) registers which allow for ultra45;low45;latency lookups in batch. We leverage this unique capability of CPUs to propose NoMAD45;Attention an efficient attention algorithm that replaces MAD operations with in45;register lookups. Through hardware45;aware algorithmic designs NoMAD45;Attention achieves the computation of attention scores using repeated fast accesses to SIMD registers despite their highly limited sizes. Moreover NoMAD45;Attention works with pre45;trained attention45;based LLMs without model finetuning. Empirical evaluations demonstrate that NoMAD45;Attention maintains the quality of the original LLMs well and speeds up the 445;bit quantized LLaMA45;7B45;based model by up to 2× at 16k context length. Our results are reproducible at https://github.com/tonyzhang617/nomad&#45;dist.
